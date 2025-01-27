---
UID: NC:d3d12umddi.PFND3D12DDI_CALCPRIVATEELEMENTLAYOUTSIZE
title: PFND3D12DDI_CALCPRIVATEELEMENTLAYOUTSIZE (d3d12umddi.h)
description: The CalcPrivateElementLayoutSize function determines the size of the user-mode display driver's private region of memory (that is, the size of internal driver structures, not the size of the resource video memory) for an element layout.
ms.assetid: 0de50da1-011c-4595-bd82-c0f17e11f595
ms.date: 10/19/2018
ms.topic: callback
f1_keywords:
 - "d3d12umddi/PFND3D12DDI_CALCPRIVATEELEMENTLAYOUTSIZE"
req.header: d3d12umddi.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
- apiref
api_type: 
- UserDefined
api_location: 
- d3d12umddi.h
api_name: 
- PFND3D12DDI_CALCPRIVATEELEMENTLAYOUTSIZE
product: 
- Windows
targetos: Windows
tech.root: display
dev_langs:
 - c++
ms.custom: RS5
---

# PFND3D12DDI_CALCPRIVATEELEMENTLAYOUTSIZE callback function

## -description

The CalcPrivateElementLayoutSize function determines the size of the user-mode display driver's private region of memory (that is, the size of internal driver structures, not the size of the resource video memory) for an element layout.

## -prototype

```cpp
//Declaration

PFND3D12DDI_CALCPRIVATEELEMENTLAYOUTSIZE Pfnd3d12ddiCalcprivateelementlayoutsize; 

// Definition

SIZE_T Pfnd3d12ddiCalcprivateelementlayoutsize 
(
	 D3D12DDI_HDEVICE
	CONST D3D12DDIARG_CREATEELEMENTLAYOUT *
)
{...}

PFND3D12DDI_CALCPRIVATEELEMENTLAYOUTSIZE 


```

## -parameters

### -param D3D12DDI_HDEVICE  

A handle to the display device (graphics context).
 
### -param * 



## -returns

Returns SIZE_T.

## -remarks




## -see-also
