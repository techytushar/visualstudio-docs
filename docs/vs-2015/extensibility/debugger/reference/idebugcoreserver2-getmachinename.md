---
title: "IDebugCoreServer2::GetMachineName | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugCoreServer2::GetName"
helpviewer_keywords: 
  - "IDebugCoreServer2::GetName"
ms.assetid: 693bd794-7215-4f07-8651-b57366d39953
caps.latest.revision: 12
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugCoreServer2::GetMachineName
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugCoreServer2::GetMachineName](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugcoreserver2-getmachinename).  
  
Gets the name of the machine the core server is running on.  
  
## Syntax  
  
```cpp#  
HRESULT GetName(   
   BSTR* pbstrName  
);  
```  
  
```csharp  
int GetName(   
   out string pbstrName  
);  
```  
  
#### Parameters  
 `pbstrName`  
 [out] Returns a string containing the name of the machine.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugCoreServer2](../../../extensibility/debugger/reference/idebugcoreserver2.md)

