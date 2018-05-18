---
title: HBA\_LoadLibrary routine
description: The HBA\_LoadLibrary routine loads and initializes the system-supplied fibre channel HBA API library.
ms.assetid: 'f71be39c-4b0c-47fc-a9d5-dfe69d8b11f2'
keywords: ["HBA_LoadLibrary routine Storage Devices"]
topic_type:
- apiref
api_name:
- HBA_LoadLibrary
api_location:
- Hbaapi.dll
api_type:
- DllExport
---

# HBA\_LoadLibrary routine

The **HBA\_LoadLibrary** routine loads and initializes the system-supplied fibre channel HBA API library.

## Syntax


```C++
HBA_STATUS HBA_API HBA_LoadLibrary(void);
```



## Parameters

This routine has no parameters.

## Return value

The **HBA\_LoadLibrary** routine returns a value of type [HBA\_STATUS](https://msdn.microsoft.com/library/windows/hardware/ff557233) that indicates the status of the HBA. In particular, **HBA\_LoadLibrary** returns one of the following qualifiers.



| Return code                                                                                                        | Description                                                                                                                   |
|--------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| <dl> <dt>**HBA\_STATUS\_OK**</dt> </dl>                     | Returned if the library loaded properly. <br/>                                                                          |
| <dl> <dt>**HBA\_STATUS\_ERROR\_ALREADY\_LOADED**</dt> </dl> | Returned if the library is already loaded.<br/>                                                                         |
| <dl> <dt>**HBA\_STATUS\_ERROR\_INCOMPATIBLE**</dt> </dl>    | Returned if **HBA\_LoadLibrary** discovered incompatibilities between the library and the associated HBA drivers. <br/> |
| <dl> <dt>**HBA\_STATUS\_ERROR**</dt> </dl>                  | Returned if an unspecified error occurred that prevented the library from loading. <br/>                                |



�

## Requirements



|                            |                                                                                                        |
|----------------------------|--------------------------------------------------------------------------------------------------------|
| Target platform<br/> | <dl> <dt>Desktop</dt> </dl>                     |
| Header<br/>          | <dl> <dt>Hbaapi.h (include Hbaapi.h)</dt> </dl> |
| Library<br/>         | <dl> <dt>Hbaapi.lib</dt> </dl>                  |
| DLL<br/>             | <dl> <dt>Hbaapi.dll</dt> </dl>                  |



## See also

<dl> <dt>

[HBA\_STATUS](https://msdn.microsoft.com/library/windows/hardware/ff557233)
</dt> </dl>

�

�

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bstorage\storage%5D:%20HBA_LoadLibrary%20routine%20%20RELEASE:%20%283/29/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")





