﻿---
title: CustomerSqlServerDatabaseAccessor.ValidateAccountActivationRequest Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices)
TOCTitle: ValidateAccountActivationRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.ValidateAccountActivationRequest(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.customersqlserverdatabaseaccessor.validateaccountactivationrequest(v=AX.60)
ms:contentKeyID: 65322891
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.ValidateAccountActivationRequest
dev_langs:
- CSharp
- C++
- VB
---

# ValidateAccountActivationRequest Method

Validate the account activation request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function ValidateAccountActivationRequest ( _
    email As String, _
    activationToken As String _
) As Boolean
'Usage
Dim instance As CustomerSqlServerDatabaseAccessor
Dim email As String
Dim activationToken As String
Dim returnValue As Boolean

returnValue = instance.ValidateAccountActivationRequest(email, _
    activationToken)
```

``` csharp
public bool ValidateAccountActivationRequest(
    string email,
    string activationToken
)
```

``` c++
public:
bool ValidateAccountActivationRequest(
    String^ email, 
    String^ activationToken
)
```

#### Parameters

  - email  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if the request is valid; otherwise return false.  

## See Also

#### Reference

[CustomerSqlServerDatabaseAccessor Class](customersqlserverdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)
