---
Description: The \_NewEnum property of OIDs retrieves an IEnumVARIANT interface on an object that can be used to enumerate the collection. This property is hidden within Visual Basic Scripting Edition (VBScript).
ms.assetid: 7c09fd11-064b-451e-bd6b-e6c13ab228a0
title: OIDs.\_NewEnum property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# OIDs.\_NewEnum property

\[The **\_NewEnum** property is available for use in the operating systems specified in the Requirements section. Instead, use the [**OidCollection Class**](https://www.bing.com/search?q=**OidCollection+Class**) in the [**System.Security.Cryptography**](https://www.bing.com/search?q=**System.Security.Cryptography**) namespace.\]

The **\_NewEnum** property retrieves an [**IEnumVARIANT**](https://msdn.microsoft.com/windows/desktop/139e3c93-faef-4003-9079-e0e94494db3e) interface on an object that can be used to enumerate the collection. This property is hidden within Visual Basic Scripting Edition (VBScript).

## Syntax


```VB
OIDs._NewEnum As IUnknown
```



## Property value

An [**IEnumVARIANT**](https://msdn.microsoft.com/windows/desktop/139e3c93-faef-4003-9079-e0e94494db3e) interface on an object that can be used to enumerate the collection.

## Remarks

This property is automatically used internally when you use the `For Each In` construct in Visual Basic Scripting Edition (VBScript).

## Requirements



|                            |                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------|
| Redistributable<br/> | CAPICOM 2.0 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>             | <dl> <dt>Capicom.dll</dt> </dl> |



## See also

<dl> <dt>

[**OIDs**](oids.md)
</dt> </dl>

 

 



