# ENCSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCSubLayer.yml" sourcestartlinenumber="1">Represents a sublayer within an ENC layer.</p>


## Object Signature

```csharp
public sealed class ENCSubLayer : Layer, IMetadataInfo, IMetadataSource
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCSubLayer.yml" sourcestartlinenumber="1">Gets the layer's definition which is null for ENC sublayers.</p>


```csharp
public override CIMBaseLayer GetDefinition()
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCSubLayer.yml" sourcestartlinenumber="1">Gets the status of the legend.</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```
### SupportsMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCSubLayer.yml" sourcestartlinenumber="1">Gets whether the ENCSubLayer supports metadata</p>


```csharp
public override bool SupportsMetadata { get; }
```


