# ReportConfigurationService.Analyze Method (IEnumerable(ReportConfiguration), IEnumerable(Application), IEnumerable(OSPatch), PropertyChangedEventHandler, SynchronizationContext, Boolean)
 

Triggers an analysis of the specified applications against this <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Analysis Analyze(
	IEnumerable<ReportConfiguration> reportingConfigurations,
	IEnumerable<Application> applications,
	IEnumerable<OSPatch> patches,
	PropertyChangedEventHandler propertyChangedHandler,
	SynchronizationContext context,
	bool forceReanalysis
)
```

###VB
```vbnet
Public Function Analyze ( 
	reportingConfigurations As IEnumerable(Of ReportConfiguration),
	applications As IEnumerable(Of Application),
	patches As IEnumerable(Of OSPatch),
	propertyChangedHandler As PropertyChangedEventHandler,
	context As SynchronizationContext,
	forceReanalysis As Boolean
) As Analysis
```


#### Parameters
&nbsp;<dl><dt>reportingConfigurations</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>)<br />The collection of <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> objects with which to analyze the applications.</dd><dt>applications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />The collection of applications to analyze.</dd><dt>patches</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_OSPatch">OSPatch</a>)<br />The collection of patches to analyze.</dd><dt>propertyChangedHandler</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/hyza7z75" target="_blank">System.ComponentModel.PropertyChangedEventHandler</a><br />The event handler to be called when the state of the analysis changes.</dd><dt>context</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/wx31754f" target="_blank">System.Threading.SynchronizationContext</a><br />A <a href="http://msdn2.microsoft.com/en-us/library/wx31754f" target="_blank">SynchronizationContext</a> that governs which thread any notification events are raised on. See the remarks of Application.Import for more details.</dd><dt>forceReanalysis</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />If `true` then applications will be re-analyzed, otherwise analysis will run only if application state requires it.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Analysis">Analysis</a><br />An <a href="T_Citrix_SDK_AppDNA_Analysis">Analysis</a> object which can be used to track the progress of the analysis.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportConfigurationService">ReportConfigurationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportConfigurationService_Analyze">Analyze Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />