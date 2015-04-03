---
title: Change Filter Items
page_title: Change Filter Items | UI for ASP.NET AJAX Documentation
description: Change Filter Items
slug: grid/functionality/filtering/how-to/change-filter-items
tags: change,filter,items
published: True
position: 3
---

# Change Filter Items



## 

You can change the appearance of the items in the filtering item (the filter textbox and filter menu image). For example, you may want to change the height and width of the default filter textbox to prevent it from wrapping text or hiding the filter menu image. You can change the url for the default filter menu image to use your own custom image.

In case you would like to set the width for the filter control declaratively, use the __FilterControlWidth__ property of the corresponding grid column to define the width dimension of the filter input.For programmatic solution or when you would like to alter the settings for the filtering image:

1. Create a handler for the grid's __ItemCreated__ event.

1. In the __ItemCreated__ event handler, check whether the item is of type __GridFilteringItem__.

1. Retrieve a reference to the __TextBox__ inside this item for the column of interest (or for each column in turn).

1. Set the properties of the __TextBox__.

The following example illustrates this technique to change the width of the text box:

>tabbedCode

````C#
	
	
	    protected void RadGrid1_ItemCreated(object sender, GridItemEventArgs e)
	    {
	        if (e.Item is GridFilteringItem)
	        {
	            GridFilteringItem filteringItem = e.Item as GridFilteringItem;
	            //set dimensions for the filter textbox  
	            TextBox box = filteringItem["ContactName"].Controls[0] as TextBox;
	            box.Width = Unit.Pixel(30);
	        }
	    }
	
````



````VB.NET
	    Protected Sub RadGrid1_ItemCreated(ByVal sender As Object, ByVal e As GridItemEventArgs) Handles RadGrid1.ItemCreated
	        If TypeOf e.Item Is GridFilteringItem Then
	            Dim filteringItem As GridFilteringItem = CType(e.Item, GridFilteringItem)
	            'set dimensions for the filter textbox   
	            Dim box As TextBox = CType(filteringItem("ContactName").Controls(0), TextBox)
	            box.Width = Unit.Pixel(30)
	        End If
	    End Sub
````


>end

If you want to show a tooltip for the filter control, you can use the __FilterControlTooltip__ property. Note that it is applicable for columns inheriting from GridBoundColumn.

In order to change the filtering image or its tooltip, use the __FilterImageUrl__or __FilterImageToolTip__properties of the corresponding grid column (either declaratively or programmatically).

How to customize auto-generated/declarative columns in RadGrid at runtime you can learn from [this topic]({%slug grid/columns/using-columns%}) (paragraph Customizing columns programmatically).