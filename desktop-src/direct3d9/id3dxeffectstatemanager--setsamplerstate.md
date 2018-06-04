---
Description: A callback function that must be implemented by a user to set a sampler.
ms.assetid: 1e19e8cd-341d-4372-9182-8b3c82155407
title: ID3DXEffectStateManager::SetSamplerState method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# ID3DXEffectStateManager::SetSamplerState method

A callback function that must be implemented by a user to set a sampler.

## Syntax


```C++
HRESULT SetSamplerState(
  [in] DWORD               Sampler,
  [in] D3DSAMPLERSTATETYPE Type,
  [in] DWORD               Value
);
```



## Parameters

<dl> <dt>

*Sampler* \[in\]
</dt> <dd>

Type: **[**DWORD**](https://msdn.microsoft.com/windows/desktop/4553cafc-450e-4493-a4d4-cb6e2f274d46)**

The zero-based sampler number.

</dd> <dt>

*Type* \[in\]
</dt> <dd>

Type: **[**D3DSAMPLERSTATETYPE**](https://msdn.microsoft.com/windows/desktop/03a6a5f1-5e4f-4ba8-be4a-74d78fbc85d0)**

Identifies sampler state, which can specify the filtering, addressing, or the border color. See [**D3DSAMPLERSTATETYPE**](https://msdn.microsoft.com/windows/desktop/03a6a5f1-5e4f-4ba8-be4a-74d78fbc85d0).

</dd> <dt>

*Value* \[in\]
</dt> <dd>

Type: **[**DWORD**](https://msdn.microsoft.com/windows/desktop/4553cafc-450e-4493-a4d4-cb6e2f274d46)**

A value from one of the sampler state types in Type.

</dd> </dl>

## Return value

Type: **[**HRESULT**](https://msdn.microsoft.com/windows/desktop/455d07e9-52c3-4efb-a9dc-2955cbfd38cc)**

The user-implemented method should return S\_OK. If the callback fails when setting the device state, either of the following will occur:

-   The effect will fail during [**ID3DXEffect::BeginPass**](id3dxeffect--beginpass.md).
-   The dynamic effect state call (such as [**IDirect3DDevice9::SetSamplerState**](/windows/desktop/api/d3d9helper/nf-d3d9-idirect3ddevice9-setsamplerstate)) will fail.

## Requirements



|                    |                                                                                          |
|--------------------|------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3DX9Effect.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3dx9.lib</dt> </dl>     |



## See also

<dl> <dt>

[ID3DXEffectStateManager](id3dxeffectstatemanager.md)
</dt> </dl>

 

 



