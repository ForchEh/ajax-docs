---
title: Telerik.Web.UI.PivotGrid.Queryable.QueryableFieldDescriptionsProvider
page_title: Telerik.Web.UI.PivotGrid.Queryable.QueryableFieldDescriptionsProvider
description: Telerik.Web.UI.PivotGrid.Queryable.QueryableFieldDescriptionsProvider
---

# Telerik.Web.UI.PivotGrid.Queryable.QueryableFieldDescriptionsProvider

Represents an Telerik.Web.UI.PivotGrid.Core.Fields.IFieldDescriptionProvider for System.Linq.IQueryable .

## Inheritance Hierarchy

* System.Object
* Telerik.Web.UI.PivotGrid.Core.Fields.FieldDescriptionProviderBase : IFieldDescriptionProvider
* Telerik.Web.UI.PivotGrid.Core.Fields.LocalFieldDescriptionsProviderBase
* Telerik.Web.UI.PivotGrid.Queryable.QueryableFieldDescriptionsProvider

## Properties

###  CurrentState `Object`

Gets the object which FieldDescriptions are generated.

###  IsBusy `Boolean`

## Methods

###  GenerateDescriptionsData

#### Returns

`Telerik.Web.UI.PivotGrid.Core.Fields.IFieldInfoData` 

###  GenerateDescriptionsData

Retrieves the DescriptionsData for data source.

#### Returns

`Telerik.Web.UI.PivotGrid.Core.Fields.IFieldInfoData` DescriptionsData instance.

###  GetDescriptionsDataAsync

#### Returns

`System.Void` 

###  GetDescriptionsDataAsync

#### Returns

`System.Void` 

###  GetDescriptionsDataAsync

#### Returns

`System.Void` 

###  GetFieldDescriptionHierarchy

Gets the field description hierarchy.

#### Parameters

#### fieldInfos `System.Collections.Generic.IEnumerable{Telerik.Web.UI.PivotGrid.Core.Fields.IPivotFieldInfo}`

Collection of  instances.

#### Returns

`Telerik.Web.UI.PivotGrid.Core.Fields.ContainerNode` 

###  OnDescriptionsDataCompleted

#### Returns

`System.Void` 

###  OnDescriptionsDataCompleted

Raise GetDescriptionsDataAsyncCompleted event.

#### Parameters

#### args `Telerik.Web.UI.PivotGrid.Core.Fields.GetDescriptionsDataCompletedEventArgs`

The event args used to invoke the event.

#### Returns

`System.Void` 

