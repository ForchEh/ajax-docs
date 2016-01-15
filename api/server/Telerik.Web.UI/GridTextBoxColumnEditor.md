---
title: Telerik.Web.UI.GridTextBoxColumnEditor
page_title: Telerik.Web.UI.GridTextBoxColumnEditor
description: Telerik.Web.UI.GridTextBoxColumnEditor
---

# Telerik.Web.UI.GridTextBoxColumnEditor

Class tha implements data editing of a GridBoundColumn with a single TextBox control.

## Inheritance Hierarchy

* System.Object
* System.Web.UI.Control
* Telerik.Web.UI.GridColumnEditorBase : IGridColumnEditor
* Telerik.Web.UI.GridTextColumnEditor
* Telerik.Web.UI.GridTextBoxColumnEditor

## Properties

###  ContainerControl `Control`

Gets the instance of the Container control (generally a TableCell), after the last call of InstantiateInControl method

###  IsInEditMode `Boolean`

Get a value indicating whether the current row/column editor is in edit mode.

###  IsInitialized `Boolean`

Get value if the editor has been initialized after an InitializeInControl or InitializeFromControl method call

###  IsInitialized `Boolean`

Get value if the editor has been initialized after an InitializeInControl or InitializeFromControl method call

###  Text `String`

Gets or sets the cell text.

###  Text `String`

Gets or sets the cell text.

###  TextBoxControl `TextBox`

Gets The text box instance created of extracted from a cell after calls to AddControlsToContainer or LoadControlsFromContainer methods.

###  TextBoxMaxLength `String`

Gets or sets the text box control MaxLength property.

###  TextBoxMode `String`

Gets or sets the text box control  property.

###  TextBoxStyle `Style`

Gets the instace of the Style that would be applied to the TextBox control, when initializing in a TableCell.

###  ToolTip `String`

The ToolTip that will be applied to the  control.

## Methods

###  AddControlsToContainer

Implement this member to create the edit controls in the grid cell.
            This method is called from each column's InitializeCell method, when a  initializes its cells.

#### Returns

`System.Void` 

###  CopySettingsFrom

Copy setting from given column editor

#### Parameters

#### editor `Telerik.Web.UI.IGridColumnEditor`

#### Returns

`System.Void` 

###  CreateControls

Create the input/edit controls belonging to the editor and prepare for AddControlsToContainer call.

#### Returns

`System.Void` 

###  LoadControlsFromContainer

This method should recrteate the state of the column editor (edit controls, etc) from the container.
            This method is called when  method is called, or when
            GridEditableItem.EditManager.GetColumnEditor is called.

#### Remarks
This method is should prepare the column editor to extract values from the edit controls residign in a TableCell of the grid.

#### Returns

`System.Void` 

