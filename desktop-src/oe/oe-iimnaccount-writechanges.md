---
title: IImnAccount WriteChanges method
description: Saves changes without sending a notification.
ms.assetid: 'e19302a0-0380-442a-94be-b18f0a2786b6'
keywords: ["WriteChanges method Windows Mail (formerly Outlook Express)", "WriteChanges method Windows Mail (formerly Outlook Express) , IImnAccount interface", "IImnAccount interface Windows Mail (formerly Outlook Express) , WriteChanges method"]
topic_type:
- apiref
api_name:
- IImnAccount.WriteChanges
api_location:
- Msoeacct.dll
api_type:
- COM
---

# IImnAccount::WriteChanges method

\[**IImnAccount::WriteChanges** is available for use in the operating systems specified in the Requirements section. It may be altered or unavailable in subsequent versions.\]

Saves changes without sending a notification.

## Syntax


```C++
HRESULT WriteChanges();
```



## Parameters

This method has no parameters.

## Return value

Type: **HRESULT**

Returns one of the following values.



| Return code                                                                                          | Description                                                          |
|------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| <dl> <dt>**S\_OK**</dt> </dl>                 | Indicates success.<br/>                                        |
| <dl> <dt>**E\_FAIL**</dt> </dl>               | Indicates an unknown error has occurred.<br/>                  |
| <dl> <dt>**E\_NoPropData**</dt> </dl>         | Indicates that the AP\_ACCOUNT\_NAME property is not set.<br/> |
| <dl> <dt>**E\_BadFriendlyName**</dt> </dl>    | Indicates that the account name is invalid.<br/>               |
| <dl> <dt>**E\_RegOpenKeyFailed**</dt> </dl>   | Indicates that the registry key cannot be opened.<br/>         |
| <dl> <dt>**E\_RegCreateKeyFailed**</dt> </dl> | Indicates that a registry key cannot be created.<br/>          |
| <dl> <dt>**E\_RegSetValueFailed**</dt> </dl>  | Indicates that a value cannot be set in the registry.<br/>     |



�

## Remarks

If the account is new and has the same name as an existing account in the registry, a unique account name is generated by adding a number (x) to the end of the account name. The number increments with every new account that has the same name.

An account name cannot be empty, contain only spaces, or contain a backslash.

Passwords are stored in an encrypted format in the registry, using the CryptoAPI.

## Requirements



|                                     |                                                                                                                |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�XP \[desktop apps only\]<br/>                                                                    |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                                           |
| Product<br/>                  | Outlook Express 6.0<br/>                                                                                 |
| Header<br/>                   | <dl> <dt>Imnact.h</dt> </dl>                            |
| IDL<br/>                      | <dl> <dt>Imnact.idl</dt> </dl>                          |
| DLL<br/>                      | <dl> <dt>Msoeacct.dll (version 6.0 or later)</dt> </dl> |



�

�




