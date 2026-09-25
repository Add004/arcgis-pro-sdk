# SubtypeFeatureLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeFeatureLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize with pre-defined properties such as renderer, visibility etc. for a sublayer and use that to create a <xref href="ArcGIS.Desktop.Mapping.SubtypeGroupLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class SubtypeFeatureLayerCreationParams
```


## Members

### SubtypeFeatureLayerCreationParams(RendererDefinition, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeFeatureLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a renderer definition and subtype Id.</p>


```csharp
public SubtypeFeatureLayerCreationParams(RendererDefinition rendererDefinition, int subTypeId)
```
### RendererDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeFeatureLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a <xref href="ArcGIS.Desktop.Mapping.RendererDefinition" data-throw-if-not-resolved="false"></xref> for the FeatureLayer represents a subtype.</p>


```csharp
public RendererDefinition RendererDefinition { get; set; }
```
### SubtypeId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeFeatureLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets subtype id. You must provide an existing subtype id.</p>


```csharp
public int SubtypeId { get; set; }
```


