# Analysis.WaitForCompletion Method (TimeSpan)
 

Waits a specific length of time for completion.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public bool WaitForCompletion(
	TimeSpan waitTimeout
)
```

###VB
```vbnet
Public Function WaitForCompletion ( 
	waitTimeout As TimeSpan
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>waitTimeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The timespan to wait for completion</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />`true` if the <a href="P_Citrix_SDK_AppDNA_Analysis_IsFinished">IsFinished</a> became `true` before *waitTimeout* expired.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Analysis">Analysis Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Analysis_WaitForCompletion">WaitForCompletion Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />