---
Description: Retrieves the name of the certificate store that this object represents.
ms.assetid: db61b464-0e8e-4b19-be12-04e00d6bba53
title: Store.Name property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Store.Name property

\[The [**Name**](store-location.md) property is available for use in the operating systems specified in the Requirements section. Instead, use the [**X509Store Class**](https://www.bing.com/search?q=**X509Store Class**) in the [**System.Security.Cryptography.X509Certificates**](https://www.bing.com/search?q=**System.Security.Cryptography.X509Certificates**) namespace.\]

The [**Name**](store-location.md) property retrieves the name of the certificate store that this object represents.

## Syntax


```VB
Store.Name As String
```



## Property value

The **String** value that represents the name of the certificate store.

## Remarks

Examples of certificate store names include My and Root.

The value of the [**Name**](store-location.md) property is the same as the value supplied for the *StoreName* parameter of the [**Open**](store-open.md) method when the store was opened.

## Requirements



|                            |                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------|
| Redistributable<br/> | CAPICOM 2.1 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>             | <dl> <dt>Capicom.dll</dt> </dl> |



## See also

<dl> <dt>

[**Store**](store.md)
</dt> </dl>

 

 



