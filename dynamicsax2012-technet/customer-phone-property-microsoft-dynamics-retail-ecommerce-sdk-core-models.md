﻿---
title: Customer.Phone Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: Phone Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer.Phone
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.customer.phone(v=AX.60)
ms:contentKeyID: 65317119
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer.Phone
dev_langs:
- CSharp
- C++
- VB
---

# Phone Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Phone As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.Phone

instance.Phone = value
```

``` csharp
[DataMemberAttribute]
public string Phone { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Phone {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)
