---
title: Telerik.Web.UI.GridSelectCommandEventArgs
page_title: Telerik.Web.UI.GridSelectCommandEventArgs
description: Telerik.Web.UI.GridSelectCommandEventArgs
---

# Telerik.Web.UI.GridSelectCommandEventArgs

For internal usage only.

## Inheritance Hierarchy

* System.Object
* System.EventArgs
* System.Web.UI.WebControls.CommandEventArgs
* Telerik.Web.UI.GridCommandEventArgs : IGridCommandEvent
* Telerik.Web.UI.GridSelectCommandEventArgs

## Properties

###  Canceled `Boolean`

Gets or sets a value, defining whether the command should be canceled.

###  CommandSource `Object`

Gets the source of the command

###  Item `GridItem`

Gets the item containing the command source

## Methods

###  ExecuteCommand

Fires RadGrid.SelectedIndexChanged event.

#### Returns

`System.Void` 

###  ExecuteCommand

Fires the command stored in 
                property

#### Returns

`System.Void` 

