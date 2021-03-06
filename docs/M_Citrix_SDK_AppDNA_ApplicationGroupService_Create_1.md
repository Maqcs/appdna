# ApplicationGroupService.Create Method (String, String, ApplicationGroup)
 

Creates an ApplicationGroup as a child group.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ApplicationGroup Create(
	string name,
	string description,
	ApplicationGroup parent
)
```

###VB
```vbnet
Public Function Create ( 
	name As String,
	description As String,
	parent As ApplicationGroup
) As ApplicationGroup
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of the new <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a>.</dd><dt>description</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The description of the new <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a>.</dd><dt>parent</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">Citrix.SDK.AppDNA.ApplicationGroup</a><br />The ApplicationGroup which is to be the parent of the new group.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a><br />The newly created ApplicationGroup.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationGroupService">ApplicationGroupService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationGroupService_Create">Create Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />