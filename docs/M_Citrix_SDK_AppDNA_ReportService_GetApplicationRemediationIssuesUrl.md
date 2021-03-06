# ReportService.GetApplicationRemediationIssuesUrl Method 
 

Gets the Application Remediation report Url for the specified application, optionally combining the results from multiple report configurations.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public string GetApplicationRemediationIssuesUrl(
	Application application,
	IEnumerable<string> reportConfigurationIdentifiers
)
```

###VB
```vbnet
Public Function GetApplicationRemediationIssuesUrl ( 
	application As Application,
	reportConfigurationIdentifiers As IEnumerable(Of String)
) As String
```


#### Parameters
&nbsp;<dl><dt>application</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Application">Citrix.SDK.AppDNA.Application</a><br />The Application object for which to export the report data.</dd><dt>reportConfigurationIdentifiers</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />A set of one or more <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> objects for which to retrieve data.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportService">ReportService Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />