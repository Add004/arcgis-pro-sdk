# PointCloudRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudRendererDefinition.yml" sourcestartlinenumber="1">A point cloud renderer definition for creating a <xref href="ArcGIS.Core.CIM.CIMPointCloudRenderer" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class PointCloudRendererDefinition : RendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudRendererDefinition.yml" sourcestartlinenumber="1">Convert a point cloud renderer definition to a CIMPointCloudRenderer using the
<xref href="ArcGIS.Desktop.Mapping.PointCloudSceneLayer.CreateRenderer(ArcGIS.Desktop.Mapping.PointCloudRendererDefinition)" data-throw-if-not-resolved="false"></xref> method.<br>
Use <xref href="ArcGIS.Desktop.Mapping.PointCloudSceneLayer.GetAvailablePointCloudRendererFields(ArcGIS.Desktop.Mapping.PointCloudRendererType)" data-throw-if-not-resolved="false"></xref> to check
whether or not a point cloud layer contains (one of) the necessary field(s) to support
the given renderer. There are up to five fields that could be available for rendering
depending on the given layer:<br>
1. ELEVATION: can be used with Stretch and ClassBreaks<br>
2. CLASS_CODE: LAS classification codes, can be used with Unique Value<br>
3. RETURNS: Lidar pulse return number, can be used with Unique Value<br>
4. RGB: can be used with RGB<br>
5. INTENSITY: can be used with Stretch and ClassBreaks<br><br></p>


## Members

### PointCloudRendererDefinition(PointCloudRendererType, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudRendererDefinition.yml" sourcestartlinenumber="1">Creates a PointCloudRendererDefinition.</p>


```csharp
public PointCloudRendererDefinition(PointCloudRendererType rendererType, string field = null)
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the field whose values will be used by the renderer.</p>


```csharp
public string Field { get; set; }
```
### RendererType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the renderer type.</p>


```csharp
public PointCloudRendererType RendererType { get; set; }
```


