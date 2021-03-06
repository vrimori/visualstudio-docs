---
title: "IEnumDebugFields::Reset | Microsoft Docs"
ms.date: "11/04/2016"
ms.topic: "conceptual"
f1_keywords: 
  - "IEnumDebugFields::Reset"
helpviewer_keywords: 
  - "IEnumDebugFields::Reset method"
ms.assetid: 38ff61e4-0120-42e8-971a-16be6050b425
author: "gregvanl"
ms.author: "gregvanl"
manager: jillfra
ms.workload: 
  - "vssdk"
---
# IEnumDebugFields::Reset
This method resets the enumeration to the first element.  
  
## Syntax  
  
```cpp  
HRESULT Reset(void);  
```  
  
```csharp  
int Reset();  
```  
  
#### Parameters  
 None  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 After this method is called, the next call to [Next](../../../extensibility/debugger/reference/ienumdebugfields-next.md) returns the first element of the enumeration.  
  
## See Also  
 [IEnumDebugFields](../../../extensibility/debugger/reference/ienumdebugfields.md)   
 [Next](../../../extensibility/debugger/reference/ienumdebugfields-next.md)