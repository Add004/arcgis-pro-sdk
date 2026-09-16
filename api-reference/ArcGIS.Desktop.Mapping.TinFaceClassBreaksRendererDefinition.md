# TinFaceClassBreaksRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Represents a class breaks renderer definition to draw faces in a surface layer.</p>


## Object Signature

```csharp
public class TinFaceClassBreaksRendererDefinition : TinColorRampRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Once you define a class breaks renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### TinFaceClassBreaksRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw faces in a surface layer.</p>


```csharp
public TinFaceClassBreaksRendererDefinition()
```
### TinFaceClassBreaksRendererDefinition(TerrainDrawCursorType, ClassificationMethod, int, CIMSymbolReference, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw faces in a surface layer.</p>


```csharp
public TinFaceClassBreaksRendererDefinition(TerrainDrawCursorType cursorType, ClassificationMethod classificationMethod = 1, int breakCount = 9, CIMSymbolReference symbolTemplate = null, CIMColorRamp colorRamp = null)
```
### CursorType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the cursor type.
The default value is <xref href="ArcGIS.Core.CIM.TerrainDrawCursorType.FaceElevation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TerrainDrawCursorType CursorType { get; set; }
```


