# StretchColorizerDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Represents a colorizer definition for a Stretch colorizer that allows you to define the range of values to be displayed and apply a color ramp
to those values.</p>


## Object Signature

```csharp
public class StretchColorizerDefinition : RasterColorizerDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">The StretchColorizerDefinition class allows you to define a simplified list of parameters to create a Stretch colorizer.
Once you define a Stretch colorizer definition, you can call the <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.CreateColorizer(ArcGIS.Desktop.Mapping.RasterColorizerDefinition)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.SetColorizer(ArcGIS.Core.CIM.CIMRasterColorizer)" data-throw-if-not-resolved="false"></xref> methods to create and assign a Stretch colorizer to a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### StretchColorizerDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Creates a default Stretch colorizer definition.</p>


```csharp
public StretchColorizerDefinition()
```
### StretchColorizerDefinition(int, RasterStretchType, double, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Creates a Stretch colorizer definition using parameters.</p>


```csharp
public StretchColorizerDefinition(int bandIndex, RasterStretchType stretchType = 1, double gamma = 1, CIMColorRamp colorRamp = null)
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### BackgroundValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the background value.</p>


```csharp
public double? BackgroundValue { get; set; }
```
### BandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the band index of the band being displayed.</p>


```csharp
public int? BandIndex { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DisplayBackgroundValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean value indicating whether or not to display the background.</p>


```csharp
public bool? DisplayBackgroundValue { get; set; }
```
### Gamma

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the gamma value.</p>


```csharp
public double? Gamma { get; set; }
```
### MaxPercent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the maximum percent for the <xref href="ArcGIS.Core.CIM.RasterStretchType.PercentMinimumMaximum" data-throw-if-not-resolved="false"></xref> stretch type.</p>


```csharp
public double? MaxPercent { get; set; }
```
### MinPercent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the minimum percent for the <xref href="ArcGIS.Core.CIM.RasterStretchType.PercentMinimumMaximum" data-throw-if-not-resolved="false"></xref> stretch type.</p>


```csharp
public double? MinPercent { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the NoData color.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### StandardDeviationsParam

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the number of standard deviations for the <xref href="ArcGIS.Core.CIM.RasterStretchType.StandardDeviations" data-throw-if-not-resolved="false"></xref> stretch type.</p>


```csharp
public double? StandardDeviationsParam { get; set; }
```
### StretchType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StretchColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Core.CIM.RasterStretchType" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterStretchType? StretchType { get; set; }
```


