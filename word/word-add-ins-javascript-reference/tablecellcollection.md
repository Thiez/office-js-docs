# TableCellCollection Object (JavaScript API for Word)

_Word 2016, Word for iPad, Word for Mac_

Contains the collection of the document's TableCell objects.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|items|[TableCell[]](tablecell.md)|A collection of tableCell objects. Read-only.|1.3||

_See property access [examples.](#property-access-examples)_

## Relationships
| Relationship | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|first|[TableCell](tablecell.md)|Gets the first table cell in this collection. Read-only.|1.3||

## Methods

| Method		   | Return Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|[getItem(index: number)](#getitemindex-number)|[TableCell](tablecell.md)|Gets a table cell object by its index in the collection.|1.3|
|[load(param: object)](#loadparam-object)|void|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|1.1|

## Method Details


### getItem(index: number)
Gets a table cell object by its index in the collection.

#### Syntax
```js
tableCellCollectionObject.getItem(index);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|:---|
|index|number|A number that identifies the index location of a table cell object.|

#### Returns
[TableCell](tablecell.md)

### load(param: object)
Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.

#### Syntax
```js
object.load(param);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|:---|
|param|object|Optional. Accepts parameter and relationship names as delimited string or an array. Or, provide [loadOption](loadoption.md) object.|

#### Returns
void