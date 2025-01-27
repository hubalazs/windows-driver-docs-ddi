---
UID: NC:d3d12umddi.PFND3D12DDI_CREATEELEMENTLAYOUT_0003
title: PFND3D12DDI_CREATEELEMENTLAYOUT_0003 (d3d12umddi.h)
description: Creates an element layout.
ms.assetid: 23cc0136-45a0-4eb3-84e6-3c906b2bbca0
ms.date: 10/19/2018
ms.topic: callback
f1_keywords:
 - "d3d12umddi/PFND3D12DDI_CREATEELEMENTLAYOUT_0003"
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
- PFND3D12DDI_CREATEELEMENTLAYOUT_0003
product: 
- Windows
targetos: Windows
tech.root: display
dev_langs:
 - c++
ms.custom: RS5
---

# PFND3D12DDI_CREATEELEMENTLAYOUT_0003 callback function

## -description

Creates an element layout.

## -prototype

```cpp
//Declaration

PFND3D12DDI_CREATEELEMENTLAYOUT_0003 Pfnd3d12ddiCreateelementlayout0003; 

// Definition

VOID Pfnd3d12ddiCreateelementlayout0003 
(
	 D3D12DDI_HDEVICE
	CONST D3D12DDIARG_CREATEELEMENTLAYOUT *
	 D3D12DDI_HELEMENTLAYOUT
)
{...}

PFND3D12DDI_CREATEELEMENTLAYOUT_0003 


```

## -parameters

### -param D3D12DDI_HDEVICE  

A handle to the display device (graphics context).
 
### -param * 

Pointer to a D3D12DDIARG_CREATEELEMENTLAYOUT structure.

### -param D3D12DDI_HELEMENTLAYOUT: 

An element layout handle.

## -returns

Returns VOID.
