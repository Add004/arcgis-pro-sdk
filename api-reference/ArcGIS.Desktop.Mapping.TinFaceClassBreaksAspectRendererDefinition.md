# TinFaceClassBreaksAspectRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksAspectRendererDefinition.yml" sourcestartlinenumber="1">Represents a class breaks renderer definition to draw faces in a surface layer.</p>


## Object Signature

```csharp
public class TinFaceClassBreaksAspectRendererDefinition : TinRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksAspectRendererDefinition.yml" sourcestartlinenumber="1">Once you define a class breaks renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### TinFaceClassBreaksAspectRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksAspectRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw faces in a surface layer.</p>


```csharp
public TinFaceClassBreaksAspectRendererDefinition()
```
### BreakCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksAspectRendererDefinition.yml" sourcestartlinenumber="1">Gets the number of class breaks. The default value is 10.</p>


```csharp
public int BreakCount { get; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksAspectRendererDefinition.yml" sourcestartlinenumber="1">Gets the classification method to be used to compute class breaks.
The default value is <xref href="ArcGIS.Core.CIM.ClassificationMethod.Manual" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; }
```
### CursorType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksAspectRendererDefinition.yml" sourcestartlinenumber="1">Gets the cursor type.
The default value is <xref href="ArcGIS.Core.CIM.TerrainDrawCursorType.FaceAspect" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TerrainDrawCursorType CursorType { get; }
```
### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceClassBreaksAspectRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a template for the symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```


