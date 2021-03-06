﻿---
title: BiometricDeviceStatusEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: BiometricDeviceStatusEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.BiometricDeviceStatusEventHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.biometricdevicestatuseventhandler(v=AX.60)
ms:contentKeyID: 49842425
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.BiometricDeviceStatusEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# BiometricDeviceStatusEventHandler Delegate

Biometric device status update event delegate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub BiometricDeviceStatusEventHandler ( _
    message As String, _
    extraData As IEnumerable(Of Byte) _
)
'Usage
Dim instance As New BiometricDeviceStatusEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void BiometricDeviceStatusEventHandler(
    string message,
    IEnumerable<byte> extraData
)
```

``` c++
public delegate void BiometricDeviceStatusEventHandler(
    String^ message, 
    IEnumerable<unsigned char>^ extraData
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - extraData  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\))\>  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

