---
title: Telerik.Charting.ExtendedLabel
page_title: Telerik.Charting.ExtendedLabel
description: Telerik.Charting.ExtendedLabel
---

# Telerik.Charting.ExtendedLabel

Base class for extended labels

## Inheritance Hierarchy

* System.Object
* Telerik.Charting.StateManagedObject : IChartingStateManagedItem, IChartingStateManager, IDisposable
* Telerik.Charting.RenderedObject : IOrdering
* Telerik.Charting.LayoutElement
* Telerik.Charting.ChartBaseLabel : IActiveRegion, ICloneable, IContainer
* Telerik.Charting.ExtendedLabel

## Properties

###  ActiveRegion `ActiveRegion`

Gets and sets Active region

###  Appearance `StyleExtendedLabel`

Gets style of label

###  Container `IContainer`

Link to container element

###  Item `LabelItem`

Gets and sets LabelItem at specified position

###  Items `LabelItem`

Items collection.

###  Marker `ChartMarker`

Graphic marker of label

###  NextPosition `Int32`

Gets a next free order position

###  OrderList `List`1`

List, that represent the render order for taken up elements

###  Parent `Object`

Gets and sets Parent element

###  PlacementDirection `PlacementDirection`

Gets and sets Direction of label position in auto mode

###  TextBlock `TextBlock`

ChartLabel TextBlock

###  ViewState `StateBag`

Sate bag to store view state content

###  ViewStateIgnoresCase `Boolean`

Gets if view sate should ignore case

###  Visible `Boolean`

Gets and sets label's visibility

## Methods

###  Add

Add element at the end of list

#### Parameters

#### element `Telerik.Charting.IOrdering`

Element

#### Returns

`System.Void` 

###  AddLabel

Add inside labels

#### Parameters

#### Label `Telerik.Charting.LabelItem`

Inside label to add

#### chartLabels `Telerik.Charting.LabelItem`

Inside labels to add

#### Returns

`System.Void` 

###  AddLabel

Add inside labels

#### Parameters

#### chartLabels `Telerik.Charting.ChartLabelsCollection`

Inside labels to add

#### Returns

`System.Void` 

###  AddLabel

Add inside labels

#### Parameters

#### chartLabels `Telerik.Charting.LabelItem`

Inside labels to add

#### Returns

`System.Void` 

###  AddLabel

Add inside labels

#### Parameters

#### labels `System.Collections.Generic.List{Telerik.Charting.LabelItem}`

Inside labels to add

#### Returns

`System.Void` 

###  BringForward

Send element at one step forward in the render order list

#### Returns

`System.Void` 

###  BringToFront

Set element at the first position in render order list

#### Returns

`System.Void` 

###  CalculatePosition

Calculates position

#### Parameters

#### renderEngine `Telerik.Charting.RenderEngine`

RenderEngine of chart

#### Returns

`System.Void` 

###  CalculatePosition

Calculates element position in container

#### Parameters

#### containerDimensions `Telerik.Charting.Styles.ISizesAndPaddings`

Rendering container dimensions

#### Returns

`System.Void` 

###  CalculatePosition

Calculates element position. Makes an additional check for a container object type

#### Parameters

#### renderEngine `Telerik.Charting.RenderEngine`

#### Returns

`System.Void` 

###  Clear

Clear LabelItems collection

#### Returns

`System.Void` 

###  Clone

Clone this object

#### Returns

`System.Object` New instance of ChartBaseLabel class with the same fields as this object

###  CloneState

Makes a view state clone

#### Returns

`System.Web.UI.StateBag` StateBag

###  Dispose

Releases unmanaged and - optionally - managed resources

#### Parameters

#### disposing `System.Boolean`

true to release both managed and unmanaged resources; false to release only unmanaged resources.

#### Returns

`System.Void` 

###  Dispose

Releases unmanaged and - optionally - managed resources

#### Parameters

#### disposing `System.Boolean`

true to release both managed and unmanaged resources; false to release only unmanaged resources.

#### Returns

`System.Void` 

###  Dispose

Releases unmanaged and - optionally - managed resources

#### Parameters

#### disposing `System.Boolean`

true to release both managed and unmanaged resources; false to release only unmanaged resources.

#### Returns

`System.Void` 

###  GetLabel

Get inner label at specified position

#### Parameters

#### index `System.Int32`

Position to get label

#### Returns

`Telerik.Charting.LabelItem` Label at specified position

###  GetMaxAvailableContentSize

Gets Available Content Size

#### Returns

`System.Drawing.SizeF` Size without margins and paddings

###  GetOffset

Gets element offset

#### Parameters

#### oelement `System.Object`

Element

#### calcMethod `Telerik.Charting.LayoutElement.OffsetCalculationDelegate`

Offset calculation method delegate (left, right, top, bottom)

#### Returns

`System.Single` Offset value

###  GetOffsetBottom

Gets bottom offset

#### Parameters

#### element `System.Object`

Element to get an offset of

#### Returns

`System.Single` Offset value

###  GetOffsetLeft

Gets left offset

#### Parameters

#### oelement `System.Object`

Element to get an offset of

#### Returns

`System.Single` Offset value

###  GetOffsetRight

Gets right offset

#### Parameters

#### element `System.Object`

Element to get an offset of

#### Returns

`System.Single` Offset value

###  GetOffsetTop

Gets top offset

#### Parameters

#### element `System.Object`

Element to get an offset of

#### Returns

`System.Single` Offset value

###  GetOrder

Gets elements order position

#### Parameters

#### element `Telerik.Charting.IOrdering`

Element

#### Returns

`System.Int32` 

###  GetOrder

Get this elements order position in container

#### Returns

`System.Int32` 

###  Insert

Insert element at specific position in list

#### Parameters

#### order `System.Int32`

Position

#### element `Telerik.Charting.IOrdering`

Element

#### Returns

`System.Void` 

###  IsVisible

Gets visibility of label

#### Returns

`System.Boolean` Visibility of label

###  IsVisible

Gets whether Label is real visible

#### Returns

`System.Boolean` Label's visibility

###  LoadViewState

load ViewState

#### Parameters

#### savedState `System.Object`

ViewState with data

#### Returns

`System.Void` 

###  LoadViewState

Load ViewState

#### Parameters

#### savedState `System.Object`

ViewState with data

#### Returns

`System.Void` 

###  LoadViewState

Loads data from a view state

#### Parameters

#### savedState `System.Object`

Views state to load from

#### Returns

`System.Void` 

###  LoadViewState

Loads data from a view state

#### Parameters

#### state `System.Object`

View state to load data from

#### Returns

`System.Void` 

###  Measure

Measure label

#### Parameters

#### renderEngine `Telerik.Charting.RenderEngine`

RenderEngine of chart

#### Returns

`System.Drawing.SizeF` Size of label

###  Measure

Measure label

#### Parameters

#### renderEngine `Telerik.Charting.RenderEngine`

Render Engine of chart

#### Returns

`System.Drawing.SizeF` Calculated size of Label

###  OnRender

Called after rendering

#### Returns

`System.Void` 

###  ReIndex

Re-index order list

#### Returns

`System.Void` 

###  Remove

Remove  element from list

#### Parameters

#### element `Telerik.Charting.IOrdering`

Element

#### Returns

`System.Void` 

###  Remove

Remove this  element from  render order list

#### Returns

`System.Void` 

###  RemoveAllLabels

Removes all inner labels

#### Returns

`System.Void` 

###  RemoveAt

Remove  element from list by it's index

#### Parameters

#### index `System.Int32`

Position

#### Returns

`System.Void` 

###  RemoveLabel

Removes inner labels

#### Parameters

#### Label `Telerik.Charting.LabelItem`

Label to remove

#### chartLabels `Telerik.Charting.LabelItem`

Labels to remove

#### Returns

`System.Void` 

###  RemoveLabel

Removes inner labels

#### Parameters

#### index `System.Int32`

Position where label should be removed

#### indexes `System.Int32`

Positions where labels should be removed

#### Returns

`System.Void` 

###  SaveViewState

Save ViewState

#### Returns

`System.Object` Saved data

###  SaveViewState

Save to ViewState

#### Returns

`System.Object` Saved data

###  SaveViewState

Saves settings to a view state

#### Returns

`System.Object` Saved view state

###  SaveViewState

Saves object data to a view state

#### Returns

`System.Object` Saved view state object

###  SendBackward

Send element at one step back in the render order list

#### Returns

`System.Void` 

###  SendToBack

Send element at the end of render order list

#### Returns

`System.Void` 

###  SetDirty

Sets the item dirty state

#### Returns

`System.Void` 

###  SetOrder

Set this object in new render order position

#### Parameters

#### index `System.Int32`

New position

#### Returns

`System.Void` 

###  Telerik.Charting.IChartingStateManager.LoadViewState

Loads data from a view state

#### Parameters

#### state `System.Object`

View state to load data from

#### Returns

`System.Void` 

###  Telerik.Charting.IChartingStateManager.SaveViewState

Saves object data to a view state

#### Returns

`System.Object` Saved view state object

###  Telerik.Charting.IChartingStateManager.TrackViewState

Tracks view state changes

#### Returns

`System.Void` 

###  TrackViewState

Track ViewState

#### Returns

`System.Void` 

###  TrackViewState

Track ViewState

#### Returns

`System.Void` 

###  TrackViewState

Tracking view state changes

#### Returns

`System.Void` 

###  TrackViewState

Tracks view state changes

#### Returns

`System.Void` 

