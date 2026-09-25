# KMLLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.KMLLayer.yml" sourcestartlinenumber="1">The KML layer represents a KML/KMZ file on disk or referenced by uri over a network or online.</p>


## Object Signature

```csharp
public sealed class KMLLayer : Layer, IMetadataInfo, IMetadataSource
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.KMLLayer.yml" sourcestartlinenumber="1">The KML layer is a read only representation and is not editable.</p>


## Members

### IsLabelVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.KMLLayer.yml" sourcestartlinenumber="1">Gets whether labels are drawing</p>


```csharp
public bool IsLabelVisible { get; }
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.KMLLayer.yml" sourcestartlinenumber="1">Gets whether the layer is selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.KMLLayer.yml" sourcestartlinenumber="1">Gets the status of the legend</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```
### OnFileChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.KMLLayer.yml" sourcestartlinenumber="1">Occurs when the file is refreshed to be updated in the map.</p>


```csharp
public event EventHandler OnFileChanged
```


