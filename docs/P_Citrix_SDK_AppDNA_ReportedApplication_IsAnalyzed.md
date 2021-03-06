# ReportedApplication.IsAnalyzed Property 
 

Gets a value indicating whether the application is analyzed.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public bool IsAnalyzed { get; }
```

###VB
```vbnet
Public ReadOnly Property IsAnalyzed As Boolean
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a>

## Remarks
<a href="T_Citrix_SDK_AppDNA_ApplicationAlgorithmResult">ApplicationAlgorithmResult</a> properties for this application are not considered valid if the application is unanalyzed or locked.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportedApplication">ReportedApplication Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />