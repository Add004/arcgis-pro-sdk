# AnnotationSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationSubLayer.yml" sourcestartlinenumber="1">Represents a sublayer within an annotation layer.</p>


## Object Signature

```csharp
public sealed class AnnotationSubLayer : Layer, IMetadataInfo, IMetadataSource
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationSubLayer.yml" sourcestartlinenumber="1">Gets the layer's definition which is null for annotation sublayers.</p>


```csharp
public override CIMBaseLayer GetDefinition()
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationSubLayer.yml" sourcestartlinenumber="1">Gets the status of the legend.</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```
### SupportsMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationSubLayer.yml" sourcestartlinenumber="1">Gets whether the AnnotationSubLayer supports metadata</p>


```csharp
public override bool SupportsMetadata { get; }
```


