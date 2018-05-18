﻿---
Description: 'Retrieves the content of the user notice.'
ms.assetid: 'dcf73357-253d-4160-be4e-f826296f5eaa'
title: 'Qualifier.ExplicitText property'
---

# Qualifier.ExplicitText property

\[The **ExplicitText** property is available for use in the operating systems specified in the Requirements section. Instead, use the [**X509Extension Class**](T:System.Security.Cryptography.X509Certificates.X509Extension) in the [**System.Security.Cryptography.X509Certificates**](frlrfSystemSecurityCryptographyX509Certificates) namespace by calling the constructor that takes an OID as a parameter, and then use the OID for Certificate Policies to process qualifiers that are part of the policy information in the Certificate Policies extension.\]

The **ExplicitText** property retrieves the content of the user notice. This property may be empty.

## Syntax


```VB
Qualifier.ExplicitText As String
```



## Property value

The content of the user notice.

## Requirements



|                            |                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------|
| Redistributable<br/> | CAPICOM 2.0 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>             | <dl> <dt>Capicom.dll</dt> </dl> |



## See also

<dl> <dt>

[**Qualifier**](qualifier.md)
</dt> </dl>

 

 



