---
title: "IDiaEnumInjectedSources::Skip | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IDiaEnumInjectedSources::Skip method"
ms.assetid: 4aad6a51-f2d3-4064-b216-60d830d0a560
caps.latest.revision: 10
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# IDiaEnumInjectedSources::Skip
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDiaEnumInjectedSources::Skip](https://docs.microsoft.com/visualstudio/debugger/debug-interface-access/idiaenuminjectedsources-skip).  
  
Skips a specified number of injected sources in an enumeration sequence.  
  
## Syntax  
  
```cpp#  
HRESULT Skip (   
   ULONG celt  
);  
```  
  
#### Parameters  
 celt  
 [in] The number of injected sources in the enumeration sequence to skip.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` if there are no more injected sources to skip.  
  
## See Also  
 [IDiaEnumInjectedSources](../../debugger/debug-interface-access/idiaenuminjectedsources.md)



