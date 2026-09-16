# ENCLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCLayer.yml" sourcestartlinenumber="1">Represents an ENC layer.</p>


## Object Signature

```csharp
public class ENCLayer : CompositeLayerWithTables, IMetadataInfo, IMetadataSource, ILayerContainer, IStandaloneTableContainer
```


## Members

### IsS101

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCLayer.yml" sourcestartlinenumber="1">Gets whether the layer references a S101 cell.</p>


```csharp
public bool IsS101 { get; }
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCLayer.yml" sourcestartlinenumber="1">Gets whether the layer is selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCLayer.yml" sourcestartlinenumber="1">Gets the status of the legend</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```


