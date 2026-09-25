# TinColorRampRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Represents a color ramp renderer definition to draw all objects in a surface layer.</p>


## Object Signature

```csharp
public abstract class TinColorRampRendererDefinition : TinRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Once you define a color ramp renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### BreakCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the number of desired class breaks. The default value is 9.</p>


```csharp
public int BreakCount { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the classification method to be used to compute class breaks.
The default value is <xref href="ArcGIS.Core.CIM.ClassificationMethod.EqualInterval" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the color ramp used for symbol colors to be assigned from.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### CursorType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Gets the cursor type.
The default value is <xref href="ArcGIS.Core.CIM.TerrainDrawCursorType.FaceElevation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TerrainDrawCursorType CursorType { get; protected set; }
```
### DeviationInterval

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the standard deviation interval.  The default value is <xref href="ArcGIS.Desktop.Mapping.StandardDeviationInterval.One" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StandardDeviationInterval DeviationInterval { get; set; }
```
### IntervalSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the interval size.</p>


```csharp
public double IntervalSize { get; set; }
```
### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinColorRampRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a template for the symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```


