---
title: IVMVirtualServer MaximumFloppyDrivesPerVM property
description: The MaximumFloppyDrivesPerVM property contains the maximum number of floppy drives per virtual machine.
ms.assetid: '29ed5e01-129a-4f80-9451-d445b0fe3350'
keywords: ["MaximumFloppyDrivesPerVM property Virtual Server", "MaximumFloppyDrivesPerVM property Virtual Server , IVMVirtualServer interface", "IVMVirtualServer interface Virtual Server , MaximumFloppyDrivesPerVM property", "MaximumFloppyDrivesPerVM property Virtual Server , VMVirtualServer class", "VMVirtualServer class Virtual Server , MaximumFloppyDrivesPerVM property"]
topic_type:
- apiref
api_name:
- IVMVirtualServer.MaximumFloppyDrivesPerVM
- IVMVirtualServer.get_MaximumFloppyDrivesPerVM
- VMVirtualServer.MaximumFloppyDrivesPerVM
api_location:
- VsComInterfaces.h
api_type:
- COM
---

# IVMVirtualServer::MaximumFloppyDrivesPerVM property

The **MaximumFloppyDrivesPerVM** property contains the maximum number of floppy drives per virtual machine.

This property is read-only.

## Syntax


```C++
HRESULT get_MaximumFloppyDrivesPerVM(
  [out]�long *maxDrives
);
```

<span codelanguage="VisualBasic"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>VB</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre><code>VMVirtualServer.MaximumFloppyDrivesPerVM( _
  ByRef maxDrives _
)</code></pre></td>
</tr>
</tbody>
</table>



## Property value

The maximum number of floppy drives per virtual machine.

This property value is read-only.

## Error codes



| Name                                                                                          | Meaning                                  |
|-----------------------------------------------------------------------------------------------|------------------------------------------|
| <dl> <dt>S\_OK</dt> </dl>              | The operation was successful.<br/> |
| <dl> <dt>E\_POINTER</dt> </dl>         | *maxDrives* is **NULL**.<br/>      |
| <dl> <dt>DISP\_E\_EXCEPTION</dt> </dl> | An unexpected error occurred.<br/> |



## Examples

The following example displays the **MaximumFloppyDrivesPerVM** property value of the [**VMVirtualServer**](ivmvirtualserver.md) object.


```VB
Set objVS = CreateObject("VirtualServer.Application")

Wscript.Echo "Name: " & objVS.Name
Wscript.Echo "Maximum floppy drives per VM: " & _
              objVS.MaximumFloppyDrivesPerVM
```



## Requirements



|                     |                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------|
| Product<br/>  | Microsoft Virtual Server 2005 onWindows Server�2003<br/>                                    |
| Download<br/> | Microsoft Virtual Server 2005 R2 SP1 Update onWindows Server�2008orWindows Server�2003<br/> |
| Header<br/>   | <dl> <dt>VsComInterfaces.h</dt> </dl>      |



## See also

<dl> <dt>

[**IVMVirtualServer**](ivmvirtualserver.md)
</dt> </dl>

�

�




