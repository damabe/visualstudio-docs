---
description: "Makes a copy of an IDiaEnumSymbolsByAddr object."
title: "IDiaEnumSymbolsByAddr::Clone"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaEnumSymbolsByAddr::Clone method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaEnumSymbolsByAddr::Clone

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Makes a copy of an object.

## Syntax

```C++
HRESULT Clone ( 
   IDiaEnumSymbolsByAddr** ppenum
);
```

#### Parameters
 ppenum

[out] Returns an [IDiaEnumSymbolsByAddr](../../debugger/debug-interface-access/idiaenumsymbolsbyaddr.md) object that contains a duplicate of the enumerator. The symbols are not duplicated, only the enumerator.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## See also
- [IDiaEnumSymbolsByAddr](../../debugger/debug-interface-access/idiaenumsymbolsbyaddr.md)
