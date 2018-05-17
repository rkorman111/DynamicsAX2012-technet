﻿---
title: OfflineDatabaseChunk.FilePath Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FilePath Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.FilePath
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.offlinedatabasechunk.filepath(v=AX.60)
ms:contentKeyID: 65316558
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.FilePath
dev_langs:
- CSharp
- C++
- VB
---

# FilePath Property

Gets or sets the path the chunk file.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FILEPATH")> _
Public Property FilePath As String
    Get
    Set
'Usage
Dim instance As OfflineDatabaseChunk
Dim value As String

value = instance.FilePath

instance.FilePath = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FILEPATH")]
public string FilePath { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FILEPATH")]
public:
property String^ FilePath {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Path of the chunk file.  

## See Also

#### Reference

[OfflineDatabaseChunk Class](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
