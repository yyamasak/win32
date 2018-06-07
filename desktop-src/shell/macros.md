---
Description: This section describes the Windows Shell utility macros.
title: Shell Macros
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Shell Macros

This section describes the Windows Shell utility macros.

## In this section



| Topic                                                                  | Description                                                                                                                                                                                                                                                     |
|------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**DEFINE\_PROPERTYKEY**](/windows/desktop/api/Propkeydef/nf-propkeydef-define_propertykey)<br/>           | Used to pack a format identifier (FMTID) and property identifier (PID) into a [**PROPERTYKEY**](https://msdn.microsoft.com/3f5f31af-f040-443b-9045-9761055381ea) structure that represents a property key.<br/>                                                                                    |
| [**IID\_PPV\_ARGS**](/windows/desktop/api/Objbase/)<br/>                      | Used to retrieve an interface pointer, supplying the IID value of the requested interface automatically based on the type of the interface pointer used. This avoids a common coding error by checking the type of the value passed at compile time.<br/> |
| [**IsEqualPropertyKey**](/windows/desktop/api/Propkeydef/nf-propkeydef-isequalpropertykey)<br/>            | Compares the members of two [**PROPERTYKEY**](https://msdn.microsoft.com/3f5f31af-f040-443b-9045-9761055381ea) structures and returns whether they are equal.<br/>                                                                                                                                 |
| [**MAKEDLLVERULL**](/windows/desktop/api/Shlwapi/nf-shlwapi-makedllverull)<br/>                      | Used to pack DLL version information into a ULONGLONG value.<br/>                                                                                                                                                                                         |
| [**NetAddr\_DisplayErrorTip**](/windows/desktop/api/Shellapi/nf-shellapi-netaddr_displayerrortip)<br/> | Displays an error message in the balloon tip associated with the network address control.<br/>                                                                                                                                                            |
| [**NetAddr\_GetAddress**](/windows/desktop/api/Shellapi/nf-shellapi-netaddr_getaddress)<br/>           | Indicates whether a network address conforms to a specified type and format.<br/>                                                                                                                                                                         |
| [**NetAddr\_GetAllowType**](/windows/desktop/api/Shellapi/nf-shellapi-netaddr_getallowtype)<br/>       | Retrieves the network address types that a specified network address control accepts.<br/>                                                                                                                                                                |
| [**NetAddr\_SetAllowType**](/windows/desktop/api/Shellapi/nf-shellapi-netaddr_setallowtype)<br/>       | Sets the network address types that a specified network address control accepts.<br/>                                                                                                                                                                     |



 

 

 



