# CircuitExportOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitExportOptions.yml" sourcestartlinenumber="1">Represents a mechanism to export the results of a trace operation</p>


## Object Signature

```csharp
public class CircuitExportOptions : ExportOptions
```


## Members

### CircuitExportOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitExportOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>CircuitExportOptions</code> class to export a <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CircuitExportOptions()
```
### ResultOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitExportOptions.yml" sourcestartlinenumber="1">Gets or sets additional options for the results included in the export.</p>


```csharp
public ResultOptions ResultOptions { get; set; }
```
### ResultTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitExportOptions.yml" sourcestartlinenumber="1">Gets or sets the list of result types to include in the export.</p>


```csharp
public IReadOnlyList<ResultType> ResultTypes { get; set; }
```
### SetAcknowledged

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitExportOptions.yml" sourcestartlinenumber="1">Gets or sets whether the export is acknowledged.</p>


```csharp
public bool SetAcknowledged { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitExportOptions.yml" sourcestartlinenumber="1">Gets or sets the spatial reference for the exported geometry result.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### TraceConfiguration

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitExportOptions.yml" sourcestartlinenumber="1">Gets or sets the trace configuration for the export.</p>


```csharp
public TraceConfiguration TraceConfiguration { get; set; }
```


