# TinFaceRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceRendererDefinition.yml" sourcestartlinenumber="1">Represents a simple renderer definition to draw all faces in a surface layer with a common symbol.</p>


## Object Signature

```csharp
public class TinFaceRendererDefinition : TinSimpleRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceRendererDefinition.yml" sourcestartlinenumber="1">The symbol used to define the <xref href="ArcGIS.Desktop.Mapping.TinSimpleRendererDefinition.SymbolTemplate" data-throw-if-not-resolved="false"></xref> should be a <xref href="ArcGIS.Core.CIM.CIMPolygonSymbol" data-throw-if-not-resolved="false"></xref>.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceRendererDefinition.yml" sourcestartlinenumber="5">Once you define a simple renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### TinFaceRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceRendererDefinition.yml" sourcestartlinenumber="1">Creates a simple renderer definition to draw faces in a surface layer.</p>


```csharp
public TinFaceRendererDefinition()
```
### TinFaceRendererDefinition(CIMSymbolReference, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinFaceRendererDefinition.yml" sourcestartlinenumber="1">Creates a simple renderer definition to draw faces in a surface layer.</p>


```csharp
public TinFaceRendererDefinition(CIMSymbolReference symbol, string label = null, string description = null)
```


