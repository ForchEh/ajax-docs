---
title: Telerik.Web.UI.TreeListExpandCollapseEventArgs
page_title: Telerik.Web.UI.TreeListExpandCollapseEventArgs
description: Telerik.Web.UI.TreeListExpandCollapseEventArgs
---

# Telerik.Web.UI.TreeListExpandCollapseEventArgs

A base class representing the event args passed when Telerik.Web.UI.RadTreeList fires the ItemCommand event with an ExpandCollapse command.

## Inheritance Hierarchy

* System.Object
* System.EventArgs
* System.Web.UI.WebControls.CommandEventArgs
* Telerik.Web.UI.TreeListCommandEventArgs : ITreeListCommandEvent
* Telerik.Web.UI.TreeListExpandCollapseEventArgs

## Properties

###  Canceled `Boolean`

Gets or sets a value indicating whether the current command is cancelled.

###  EventSource `Object`

Gets the control which was responsible for firing the event.

###  Item `TreeListItem`

The item in which the command was triggered.

## Methods

###  ExecuteCommand

Forces the control to execute the ExpandCollapse command.

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

