﻿---
title: SalesTransaction.Comment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Comment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.Comment
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.comment(v=AX.60)
ms:contentKeyID: 62214598
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.Comment
dev_langs:
- CSharp
- C++
- VB
---

# Comment Property

Gets or sets the comment associated with the sales transaction. Cannot be more than 60 characters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COMMENT")> _
Public Property Comment As String
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As String

value = instance.Comment

instance.Comment = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COMMENT")]
public string Comment { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COMMENT")]
public:
property String^ Comment {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
