# TinNodeClassBreaksRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinNodeClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Represents a class breaks renderer definition to draw nodes in a TIN layer.</p>


## Object Signature

```csharp
public class TinNodeClassBreaksRendererDefinition : TinColorRampRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinNodeClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">A TinNodeClassBreaksRendererDefinition has a fixed <xref href="ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.CursorType?text=CursorType" data-throw-if-not-resolved="false"></xref> of <xref href="ArcGIS.Core.CIM.TerrainDrawCursorType.NodeElevation" data-throw-if-not-resolved="false"></xref>
and is only applicable to TIN layers.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.TinNodeClassBreaksRendererDefinition.yml" sourcestartlinenumber="6">Once you define a class breaks renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### TinNodeClassBreaksRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinNodeClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw nodes in a TIN layer.</p>


```csharp
public TinNodeClassBreaksRendererDefinition()
```
### TinNodeClassBreaksRendererDefinition(ClassificationMethod, int, CIMSymbolReference, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinNodeClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw nodes in a TIN layer.</p>


```csharp
public TinNodeClassBreaksRendererDefinition(ClassificationMethod classificationMethod, int breakCount = 9, CIMSymbolReference symbolTemplate = null, CIMColorRamp colorRamp = null)
```


