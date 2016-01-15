---
title: Telerik.Web.UI.GridExcelBuilder.RowsCollection
page_title: Telerik.Web.UI.GridExcelBuilder.RowsCollection
description: Telerik.Web.UI.GridExcelBuilder.RowsCollection
---

# Telerik.Web.UI.GridExcelBuilder.RowsCollection

Collection of RowElement objects

## Inheritance Hierarchy

* System.Object
* Telerik.Web.UI.GridExcelBuilder.RowsCollection : ICollection, IEnumerable, IList, IRowsCollection

## Properties

###  Count `Int32`

Gets the number of elements contained in the ICollection. (Inherited from ICollection.)

###  IsFixedSize `Boolean`

Gets a value indicating whether the collection has a fixed size.

###  IsReadOnly `Boolean`

Gets a value indicating whether the collection is read-only.

###  IsSynchronized `Boolean`

Gets a value indicating whether access to the ICollection is synchronized (thread safe). (Inherited from ICollection.)

###  Item `RowElement`

Gets/sets the RowElement object by given row index

###  SyncRoot `Object`

Gets an object that can be used to synchronize access to the ICollection. (Inherited from ICollection.)

## Methods

###  Add

Adds an item to the collection.

#### Parameters

#### value `Telerik.Web.UI.GridExcelBuilder.RowElement`

The object to add to the collection.

#### Returns

`System.Int32` The position into which the new element was inserted, or -1 to indicate that the item was not inserted into the collection,

###  Clear

Removes all items from the IList.

#### Returns

`System.Void` 

###  Contains

Determines whether the collection contains a specific value.

#### Parameters

#### value `Telerik.Web.UI.GridExcelBuilder.RowElement`

The object to locate in the collection.

#### Returns

`System.Boolean` true if the object is found in the collection; otherwise, false.

###  CopyTo

Copies the elements of the ICollection to an Array, starting at a particular Array index.

#### Parameters

#### array `Telerik.Web.UI.GridExcelBuilder.RowElement`

The one-dimensional Array that is the destination of the elements copied from ICollection. The Array must have zero-based indexing.

#### index `System.Int32`

The zero-based index in array at which copying begins.

#### Returns

`System.Void` 

###  GetEnumerator

Returns an enumerator that iterates through a collection. (Inherited from IEnumerable.)

#### Returns

`System.Collections.IEnumerator` 

###  IndexOf

Determines the index of a specific item in the collection.

#### Parameters

#### value `Telerik.Web.UI.GridExcelBuilder.RowElement`

The object to locate in the collection.

#### Returns

`System.Int32` The index of value if found in the collection; otherwise, -1.

###  Insert

Inserts an item to the collection at the specified index.

#### Parameters

#### index `System.Int32`

The zero-based index at which value should be inserted.

#### value `Telerik.Web.UI.GridExcelBuilder.RowElement`

The object to insert into the collection.

#### Returns

`System.Void` 

###  Remove

Removes the first occurrence of a specific object from the collection.

#### Parameters

#### value `Telerik.Web.UI.GridExcelBuilder.RowElement`

The object to remove from the collection.

#### Returns

`System.Void` 

###  RemoveAt

Removes the collection item at the specified index.

#### Parameters

#### index `System.Int32`

The zero-based index of the item to remove.

#### Returns

`System.Void` 

