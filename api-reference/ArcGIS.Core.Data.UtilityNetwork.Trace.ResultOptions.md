# ResultOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.ResultOptions.yml" sourcestartlinenumber="1">Specifies additional field values that can be returned from a trace operation using the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.ResultType.Feature" data-throw-if-not-resolved="false"></xref> result type.</p>


## Object Signature

```csharp
public sealed class ResultOptions
```


## Members

### ResultOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.ResultOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>ResultOptions</code> class.</p>


```csharp
public ResultOptions()
```
### IncludeGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.ResultOptions.yml" sourcestartlinenumber="1">Specifies whether to include geometry information.</p>


```csharp
public bool IncludeGeometry { get; set; }
```
### NetworkAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.ResultOptions.yml" sourcestartlinenumber="1">Specifies additional network attribute values to be returned during trace.</p>


```csharp
public List<string> NetworkAttributes { get; set; }
```
### RelatedRecordFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.ResultOptions.yml" sourcestartlinenumber="1">Specifies additional related record field values to be returned during trace.</p>


```csharp
public Dictionary<RelationshipClass, List<string>> RelatedRecordFields { get; set; }
```
### ResultFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.ResultOptions.yml" sourcestartlinenumber="1">Specifies additional field values to be returned during trace.</p>


```csharp
public Dictionary<NetworkSource, List<string>> ResultFields { get; set; }
```


