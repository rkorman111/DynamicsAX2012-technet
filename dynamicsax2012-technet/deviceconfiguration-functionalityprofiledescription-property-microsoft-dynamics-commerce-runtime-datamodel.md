﻿---
title: DeviceConfiguration.FunctionalityProfileDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FunctionalityProfileDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.FunctionalityProfileDescription
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.functionalityprofiledescription(v=AX.60)
ms:contentKeyID: 62206734
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.FunctionalityProfileDescription
dev_langs:
- CSharp
- C++
- VB
---

# FunctionalityProfileDescription Property

Gets or sets the functionality profile description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NAME")> _
Public Property FunctionalityProfileDescription As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.FunctionalityProfileDescription

instance.FunctionalityProfileDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NAME")]
public string FunctionalityProfileDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NAME")]
public:
property String^ FunctionalityProfileDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The string containing functionality profile description.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
