﻿---
title: PeriodicDiscount.MixAndMatchLineGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchLineGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchLineGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.mixandmatchlinegroup(v=AX.60)
ms:contentKeyID: 49844018
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchLineGroup
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchLineGroup Property

Gets the line group for this rule if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEGROUP")> _
Public Property MixAndMatchLineGroup As String
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As String

value = instance.MixAndMatchLineGroup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEGROUP")]
public string MixAndMatchLineGroup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEGROUP")]
public:
property String^ MixAndMatchLineGroup {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
