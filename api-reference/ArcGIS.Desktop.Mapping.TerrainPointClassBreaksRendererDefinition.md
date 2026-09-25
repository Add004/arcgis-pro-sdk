# TerrainPointClassBreaksRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Represents a class breaks renderer definition to draw terrain points in a Terrain layer.</p>


## Object Signature

```csharp
public class TerrainPointClassBreaksRendererDefinition : TinColorRampRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">A TerrainPointClassBreaksRendererDefinition has a fixed <xref href="ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.CursorType?text=CursorType" data-throw-if-not-resolved="false"></xref> of <xref href="ArcGIS.Core.CIM.TerrainDrawCursorType.TerrainPointElevation" data-throw-if-not-resolved="false"></xref>
and is only applicable to Terrain layers.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="6">Once you define a class breaks renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### TerrainPointClassBreaksRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw terrain points in a Terrain layer.</p>


```csharp
public TerrainPointClassBreaksRendererDefinition()
```
### TerrainPointClassBreaksRendererDefinition(ClassificationMethod, int, CIMSymbolReference, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw terrain points in a Terrain layer.</p>


```csharp
public TerrainPointClassBreaksRendererDefinition(ClassificationMethod classificationMethod, int breakCount = 9, CIMSymbolReference symbolTemplate = null, CIMColorRamp colorRamp = null)
```


