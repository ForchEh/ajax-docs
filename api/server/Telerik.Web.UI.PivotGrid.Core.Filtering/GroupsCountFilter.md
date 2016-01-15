---
title: Telerik.Web.UI.PivotGrid.Core.Filtering.GroupsCountFilter
page_title: Telerik.Web.UI.PivotGrid.Core.Filtering.GroupsCountFilter
description: Telerik.Web.UI.PivotGrid.Core.Filtering.GroupsCountFilter
---

# Telerik.Web.UI.PivotGrid.Core.Filtering.GroupsCountFilter

Implements a Telerik.Web.UI.PivotGrid.Core.Filtering.GroupFilter that selects a specific number of groups sorted by a given criteria.

## Inheritance Hierarchy

* System.Object
* Telerik.Web.UI.PivotGrid.Core.Cloneable
* Telerik.Web.UI.PivotGrid.Core.SettingsNode : IEditable, INotifyPropertyChanged, IServiceProvider, ISupportInitialize
* Telerik.Web.UI.PivotGrid.Core.Filtering.GroupFilter
* Telerik.Web.UI.PivotGrid.Core.Filtering.SiblingGroupsFilter
* Telerik.Web.UI.PivotGrid.Core.Filtering.SortedGroupsFilter
* Telerik.Web.UI.PivotGrid.Core.Filtering.GroupsCountFilter

## Properties

###  AggregateIndex `Int32`

Specifies which aggregate description in the grouping would be used as source for comparison.

###  Comparer `IComparer`1`

Gets or sets the comparer used to sort for the .

###  Count `Int32`

Filters groups until that sum of their totals reaches that sum.

###  Parent `SettingsNode`

Gets the  this  is used in.

###  Selection `SortedListSelection`

Specifies whether the  or  groups would be accepted by the filter.

## Methods

###  AddSettingsChild

Set this  as parent of the  and becomes a target for the 's change notifications.

#### Parameters

#### child `Telerik.Web.UI.PivotGrid.Core.SettingsNode`

The nested .

#### Returns

`System.Void` 

###  BeginEdit

Enters the  in a new editing scope. Use when applying multiple changes.
            If child  are changed, notifications will be accumulated in this .
            
            using(settingsNode.BeginEdit())
            {
                // Apply multiple changes here.
            }

#### Returns

`System.IDisposable` An edit scope token that you must  when you are done with the editing.

###  BeginInit

#### Returns

`System.Void` 

###  Clone

Creates a new instance of the , making deep copies of the object's values.

#### Returns

`Telerik.Web.UI.PivotGrid.Core.Cloneable` A clone of the current object.

###  CloneCore

#### Returns

`System.Void` 

###  CloneCore

#### Returns

`System.Void` 

###  CloneCore

Makes the instance a clone (deep copy) of the specified .

#### Remarks
Notes to Inheritors
            If you derive from , you may need to override this method to copy all properties.
            It is essential that all implementations call the base implementation of this method (if you don't call base you should manually copy all needed properties including base properties).

#### Parameters

#### source `Telerik.Web.UI.PivotGrid.Core.Cloneable`

The object to clone.

#### Returns

`System.Void` 

###  CloneOrDefault

If source is null - returns default().
            If source is not null makes a copy of type .
            If the copy is from a different type throws appropriate exception.

#### Parameters

#### source ```0`

The source that is about to be copied.

#### Returns

`Telerik.Web.UI.PivotGrid.Core.T` Clone of  of type . If source is null - default().

###  CreateInstanceCore

#### Returns

`Telerik.Web.UI.PivotGrid.Core.Cloneable` 

###  CreateInstanceCore

When implemented in a derived class, creates a new instance of the  derived class.

#### Remarks
Do not call this method directly (except when calling base in an implementation). This method is called internally by the  method whenever a new instance of the  is created.
            Notes to Inheritors.
            Every  derived class must implement this method. A typical implementation is to simply call the default constructor and return the result.

#### Returns

`Telerik.Web.UI.PivotGrid.Core.Cloneable` New instance for cloning.

###  EndInit

#### Returns

`System.Void` 

###  Filter

#### Returns

`System.Collections.Generic.ICollection`1` 

###  Filter

Filters the groups within a parent group. Can filter based on count, average values or sorted values.

#### Parameters

#### groups `System.Collections.Generic.IReadOnlyList{Telerik.Web.UI.PivotGrid.Core.IGroup}`

A read only list of all siblings.

#### results `Telerik.Web.UI.PivotGrid.Core.IAggregateResultProvider`

The current aggregate results.

#### axis `Telerik.Web.UI.PivotGrid.Core.PivotAxis`

Identifies if the groups are in  or .

#### level `System.Int32`

The level of the groups.

#### Returns

`System.Collections.Generic.ICollection`1` A  implementation that is used to filter the groups.

###  GetService

#### Returns

`System.Object` 

###  GetServiceOverride

Provides services available by this SettingsNode.
            Other services may be available in its s.
            The default implementation returns this  if the desired service type is assignable from the type of this.
            The  implementation of  would query the service on the local node and if not available would query up the  nodes.

#### Parameters

#### serviceType `System.Type`

The type of the requested service.

#### Returns

`System.Object` A service instance if available, null otherwise.

###  NotifyServicesChanged

Raises the  event.

#### Returns

`System.Void` 

###  NotifySettingsChanged

Will recursively notify all  for a settings change.

#### Parameters

#### args `Telerik.Web.UI.PivotGrid.Core.SettingsChangedEventArgs`

that contain information about the change.

#### Returns

`System.Void` 

###  OnEnteredEditScope

Override to provide custom behavior for derived classes when editing begins.
             is already in edit mode and changes within the method body will be accumulated and released upon exit.

#### Returns

`System.Void` 

###  OnExitingEditScope

Override to provide custom behavior for derived classes when finishing editing.
             is still in edit mode and changes within the method body will be accumulated and released upon exit.

#### Returns

`System.Void` 

###  OnPropertyChanged

Raises this object's  event.

#### Parameters

#### propertyName `System.String`

The property that has a new value.

#### Returns

`System.Void` 

###  OnSettingsChanged

Invoked when a SettingsChangedEventArgs reaches the .

#### Parameters

#### args `Telerik.Web.UI.PivotGrid.Core.SettingsChangedEventArgs`

The  that contains the event data.

#### Returns

`System.Void` 

###  RemoveSettingsChild

Unsets the parent initiated with .
            This  will no longer receive change notifications from the .

#### Parameters

#### child `Telerik.Web.UI.PivotGrid.Core.SettingsNode`

The nested .

#### Returns

`System.Void` 

