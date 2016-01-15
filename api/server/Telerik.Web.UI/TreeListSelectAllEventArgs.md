---
title: Telerik.Web.UI.TreeListSelectAllEventArgs
page_title: Telerik.Web.UI.TreeListSelectAllEventArgs
description: Telerik.Web.UI.TreeListSelectAllEventArgs
---

# Telerik.Web.UI.TreeListSelectAllEventArgs

A base class representing the event args passed when Telerik.Web.UI.RadTreeList fires the ItemCommand event with a SelectAll command.

## Inheritance Hierarchy

* System.Object
* System.EventArgs
* System.Web.UI.WebControls.CommandEventArgs
* Telerik.Web.UI.TreeListCommandEventArgs : ITreeListCommandEvent
* Telerik.Web.UI.TreeListSelectAllEventArgs

## Properties

###  Canceled `Boolean`

Gets or sets a value indicating whether the current command is cancelled.

###  EventSource `Object`

Gets the control which was responsible for firing the event.

###  Item `TreeListItem`

The item in which the command was triggered.

## Methods

###  ExecuteCommand

Forces the execution of the SelectAll command.

#### Parameters

#### source `System.Object`

The RadTreeList object.

#### Returns

`System.Void` 

###  ExecuteCommand

Forces the execution of the command that triggered the event.

#### Parameters

#### source `System.Object`

The owner RadTreeList object

#### Returns

`System.Void` 

