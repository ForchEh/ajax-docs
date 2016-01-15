---
title:Telerik.Web.UI.SpreadsheetRange
page_title:
description:
---

# Telerik.Web.UI.SpreadsheetRange

## Methods

### get_enabled

Gets the disabled state of the cells in the range.

#### Parameters

#### Returns

`Boolean`

### set_enabled

Sets the disabled state of the cells in the range.

#### Parameters

##### value `Boolean`

#### Returns

`None`

### set_filter

Enables/disables or sets the filter for a given range.

#### Parameters

##### filter `Object`

#### Returns

`None`

### hasFilter

Returns true if the sheet of the range has filter enabled.

#### Parameters

#### Returns

`Boolean` 

### get_isSortable

Returns true if a range can be sorted.

#### Parameters

#### Returns

`Boolean`

### get_isFilterable

Returns true if a range can be filtered.

#### Parameters

#### Returns

`Boolean`

### merge

Merges the range cells into a single merged cell. If the range already includes a merged cell, they are merged, too.

#### Parameters

#### Returns

`None`

### unmerge

Un-merges any merged cells which are included in the range.

#### Parameters

#### Returns

`None`

### select

Sets the sheet selection to the range cells.

#### Parameters

#### Returns

`None`

### get_borderTopSize

Gets the size of the top border of the cells.

#### Parameters

#### Returns

`None`

### set_borderTopSize

Sets the size of the top border of the cells. If the range includes more than a single cell, the setting is applied to all cells. The method accepts any valid Length value.

#### Parameters

##### size `String`

#### Returns

`None`

### get_borderTopColor

Gets the color of the top border of the cells.

#### Parameters

#### Returns

`String`

### set_borderTopColor	

Sets the color of the top border of the cells. If the range includes more than a single cell, the setting is applied to all cells. The color may be set to any valid CSS color.

#### Parameters

##### color `String`

#### Returns

`None`

### get_borderRightSize

Gets the size of the right border of the cells.

#### Parameters

#### Returns

`Number`

### set_borderRightSize

Sets the size of the right border of the cells. If the range includes more than a single cell, the setting is applied to all cells. The method accepts any valid Length value.

#### Parameters

##### size `Number`

#### Returns

`None`

### get_borderRightColor

Gets the color of the right border of the cells.

#### Parameters 

#### Returns

`String`

### set_borderRightColor

Sets the color of the right border of the cells. If the range includes more than a single cell, the setting is applied to all cells. The color may be set to any valid CSS color.

#### Parameters

##### color `String`

#### Returns

`None`

### get_borderLeftSize

Gets the size of the left border of the cells.

#### Parameters

#### Returns

`Number`

### set_borderLeftSize

Sets the size of the left border of the cells. If the range includes more than a single cell, the setting is applied to all cells. The method accepts any valid Length value.

#### Parameters

##### size `Number`

#### Returns

`None`

### get_borderLeftColor

Gets the color of the left border of the cells.

#### Parameters

#### Returns

`String`

### set_borderLeftColor

Sets the color of the left border of the cells. If the range includes more than a single cell, the setting is applied to all cells. The color may be set to any valid CSS color.

#### Parameters

##### color `String`

#### Returns

`None`

### get_borderBottomSize

Gets the size of the bottom border of the cells.

#### Parameters

#### Returns

`Number`

### set_borderBottomSize

Sets the size of the bottom border of the cells. If the range includes more than a single cell, the setting is applied to all cells. The method accepts any valid Length value.

#### Parameters

##### size `Number`

#### Returns

`None`

### get_borderBottomColor

Gets the color of the bottom border of the cells.

#### Parameters

#### Returns

`String`

### set_borderBottomColor

Sets the color of the bottom border of the cells. If the range includes more than a single cell, the setting is applied to all cells. The color may be set to any valid CSS color.

#### Parameters

##### color `String`

#### Returns

`None`

### clearFilter

Clears the set filters for the given column(s). The indices is relative to the beginning of the range.

#### Parameters

##### indices `Array`

#### Returns

`None`

### clear

Clears the contents of the range cells.

#### Parameters

##### options? `Object`

#### Returns

`None`

### fillFrom

Fills a range with values inferred from a source range. This method employs some heuristics similar to what Excel's auto-filling algorithm does when you select a range of cells and drag the bottom-right handle. The range to be filled is the current object, and you must pass a source range containing data as first argument.

#### Parameters

##### srcRange `String`

##### direction? `Number`

#### Returns

`None`