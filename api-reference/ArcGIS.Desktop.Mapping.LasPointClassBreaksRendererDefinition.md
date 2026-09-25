# LasPointClassBreaksRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Represents a class breaks renderer definition to draw points in a LAS dataset layer.</p>


## Object Signature

```csharp
public class LasPointClassBreaksRendererDefinition : TinColorRampRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">A LasPointClassBreaksRendererDefinition has a fixed <xref href="ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.CursorType?text=CursorType" data-throw-if-not-resolved="false"></xref> of <xref href="ArcGIS.Core.CIM.TerrainDrawCursorType.TerrainPointElevation" data-throw-if-not-resolved="false"></xref>
and is only applicable to a LAS dataset layer.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="6">Once you define a class breaks renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### LasPointClassBreaksRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw points in a LAS dataset layer.</p>


```csharp
public LasPointClassBreaksRendererDefinition()
```
### LasPointClassBreaksRendererDefinition(ClassificationMethod, int, CIMSymbolReference, double, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Create a class breaks renderer definition to draw points in a LAS dataset layer.</p>


```csharp
public LasPointClassBreaksRendererDefinition(ClassificationMethod classificationMethod, int breakCount = 9, CIMSymbolReference symbolTemplate = null, double symbolScaleFactor = 0, CIMColorRamp colorRamp = null)
```
### ModulateUsingIntensity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the flag indicating whether or not to modulate using intensity.   The default value is false.</p>


```csharp
public bool ModulateUsingIntensity { get; set; }
```
### SymbolScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">The symbol scale factor. Default value is 0.0.</p>


```csharp
public double SymbolScaleFactor { get; set; }
```


