# LasStretchRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Represents a LAS stretch renderer definition.</p>


## Object Signature

```csharp
public class LasStretchRendererDefinition : TinRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Once you define a LAS stretch renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### LasStretchRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Creates a LAS stretch renderer definition.</p>


```csharp
public LasStretchRendererDefinition()
```
### LasStretchRendererDefinition(LASStretchAttribute, LASStretchType, double, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Creates a LAS stretch renderer.</p>


```csharp
public LasStretchRendererDefinition(LASStretchAttribute stretchAttribute, LASStretchType stretchType = 3, double symbolScaleFactor = 0, CIMColorRamp colorRamp = null)
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the color ramp used for symbol colors to be assigned from.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### GammaValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the gamma value. Default value is 1.0.</p>


```csharp
public double GammaValue { get; set; }
```
### ModulateUsingIntensity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the flag indicating whether or not to modulate intensity.  The default value is false.</p>


```csharp
public bool ModulateUsingIntensity { get; set; }
```
### NumberOfStandardDeviations

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">The number of standard deviations.  Default value is 2.0.</p>


```csharp
public double NumberOfStandardDeviations { get; set; }
```
### StretchAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the stretch attribute used.   Default value is <xref href="ArcGIS.Core.CIM.LASStretchAttribute.Elevation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LASStretchAttribute StretchAttribute { get; set; }
```
### StretchType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">Gets the stretch type.  Default value is <xref href="ArcGIS.Core.CIM.LASStretchType.StandardDeviations" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LASStretchType StretchType { get; set; }
```
### SymbolScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasStretchRendererDefinition.yml" sourcestartlinenumber="1">The symbol scale factor. Default value is 0.0.</p>


```csharp
public double SymbolScaleFactor { get; set; }
```


