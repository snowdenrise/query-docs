---
description: "Learn more about: MATCHBY"
title: "MATCHBY function (DAX) | Microsoft Docs"
ms.service: powerbi 
ms.subservice: dax
ms.date: 05/10/2023
ms.topic: reference
author: keshen
ms.author: owend
recommendations: false

---

# MATCHBY

In window functions, defines the columns that are used to determine how to match data and identify the current row.

## Syntax  

```dax
MATCHBY ( [<matchBy_columnName>[, matchBy_columnName [, …]]] )
```

### Parameters  

|Term|Definition|  
|--------|--------------|  
|matchBy_columnName| (Optional) The name of an existing column to be used to identify current row in the window function’s \<relation>.</br> RELATED() may also be used to refer to a column in a table related to \<relation>.|

## Return value

This function does not return a value.  

## Remarks

This function can only be used within a window function expression.

## Example

See [OFFSET](offset-function-dax.md).

## See also

[INDEX](index-function-dax.md)  
[OFFSET](offset-function-dax.md)  
[ORDERBY](orderby-function-dax.md)  
[WINDOW](window-function-dax.md)  
[RANK](rank-function-dax.md)  
[ROWNUMBER](rownumber-function-dax.md)
