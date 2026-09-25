# IGPHistoryItem

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Geoprocessing.html">Geoprocessing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPHistoryItem.yml" sourcestartlinenumber="1">Get geoprocessing tool history information from a project.</p>


## Object Signature

```csharp
public interface IGPHistoryItem
```


## Members

### GPResult

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPHistoryItem.yml" sourcestartlinenumber="1">Geoprocessing result object</p>


```csharp
IGPResult GPResult { get; }
```
### TimeStamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPHistoryItem.yml" sourcestartlinenumber="1">Creation time</p>


```csharp
DateTime TimeStamp { get; }
```
### ToolPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPHistoryItem.yml" sourcestartlinenumber="1">Full GP Tool path</p>


```csharp
string ToolPath { get; }
```


