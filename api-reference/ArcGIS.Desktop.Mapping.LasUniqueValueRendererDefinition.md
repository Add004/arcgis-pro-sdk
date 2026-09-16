# LasUniqueValueRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Represents a unique value renderer definition for a LAS dataset layer.</p>


## Object Signature

```csharp
public class LasUniqueValueRendererDefinition : TinUniqueValueRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Once you define a renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### LasUniqueValueRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Creates a unique value renderer definition to draw points in a LAS dataset layer.</p>


```csharp
public LasUniqueValueRendererDefinition()
```
### LasUniqueValueRendererDefinition(LasAttributeType, bool, CIMSymbolReference, double, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Creates a unique value renderer definition to draw points in a LAS dataset layer.</p>


```csharp
public LasUniqueValueRendererDefinition(LasAttributeType attributeType, bool modulateUsingItensity = false, CIMSymbolReference symbolTemplate = null, double symbolScaleFactor = 0, CIMColorRamp colorRamp = null)
```
### AttributeType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the attribute used to define the unique values.   The default value is <xref href="ArcGIS.Desktop.Mapping.LasAttributeType.Classification" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasAttributeType AttributeType { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the color ramp used for symbol colors to be assigned from.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### ModulateUsingIntensity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the flag indicating whether or not to modulate using intensity.   The default value is false.</p>


```csharp
public bool ModulateUsingIntensity { get; set; }
```
### SymbolScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">The symbol scale factor. Default value is 0.0.</p>


```csharp
public double SymbolScaleFactor { get; set; }
```


