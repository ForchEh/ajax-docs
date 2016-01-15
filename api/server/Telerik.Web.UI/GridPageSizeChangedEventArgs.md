---
title: Telerik.Web.UI.GridPageSizeChangedEventArgs
page_title: Telerik.Web.UI.GridPageSizeChangedEventArgs
description: Telerik.Web.UI.GridPageSizeChangedEventArgs
---

# Telerik.Web.UI.GridPageSizeChangedEventArgs

The event arguments passed when page size have changed and Telerik.Web.UI.RadGrid fires PageSizeChanged event.

## Inheritance Hierarchy

* System.Object
* System.EventArgs
* System.Web.UI.WebControls.CommandEventArgs
* Telerik.Web.UI.GridCommandEventArgs : IGridCommandEvent
* Telerik.Web.UI.GridPageSizeChangedEventArgs

## Properties

###  Canceled `Boolean`

Gets or sets a value, defining whether the command should be canceled.

###  CommandSource `Object`

Gets the source of the command

###  Item `GridItem`

Gets the item containing the command source

###  NewPageSize `Int32`

Gets the new selected page size that will be applied.

## Methods

###  ExecuteCommand

Fires the command stored in 
                property

#### Returns

`System.Void` 

