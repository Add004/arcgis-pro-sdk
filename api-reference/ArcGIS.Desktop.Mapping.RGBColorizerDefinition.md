# RGBColorizerDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Represents a colorizer definition for a RGB colorizer that enables you to create composite images by loading different multispectral
bands into each of the three channels: Red, Green and Blue.</p>


## Object Signature

```csharp
public class RGBColorizerDefinition : RasterColorizerDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">The RGBColorizerDefinition class allows you to define a simplified list of parameters to create a RGB colorizer.<br>
Once you define a RGB colorizer definition, you can call the <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.CreateColorizer(ArcGIS.Desktop.Mapping.RasterColorizerDefinition)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.SetColorizer(ArcGIS.Core.CIM.CIMRasterColorizer)" data-throw-if-not-resolved="false"></xref> methods to create and assign a RGB colorizer to a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### RGBColorizerDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Creates a default RGB colorizer definition.</p>


```csharp
public RGBColorizerDefinition()
```
### RGBColorizerDefinition(int, int, int, RasterStretchType, double, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Creates a RGB colorizer definition using parameters.</p>


```csharp
public RGBColorizerDefinition(int redBandIndex, int greenBandIndex, int blueBandIndex, RasterStretchType stretchType = 1, double gammaR = 1, double gammaG = 1, double gammaB = 1)
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### BackgroundValueBlue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the background value for the blue channel.</p>


```csharp
public double? BackgroundValueBlue { get; set; }
```
### BackgroundValueGreen

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the background value for the green channel.</p>


```csharp
public double? BackgroundValueGreen { get; set; }
```
### BackgroundValueRed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the background value for the red channel.</p>


```csharp
public double? BackgroundValueRed { get; set; }
```
### BlueBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the band index for the blue channel.</p>


```csharp
public int? BlueBandIndex { get; set; }
```
### DisplayBackgroundValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean value indicating whether or not to display the background value.</p>


```csharp
public bool? DisplayBackgroundValue { get; set; }
```
### GammaB

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the gamma value for the blue channel.</p>


```csharp
public double? GammaB { get; set; }
```
### GammaG

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the gamma value for the green channel.</p>


```csharp
public double? GammaG { get; set; }
```
### GammaR

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the gamma value for the red channel.</p>


```csharp
public double? GammaR { get; set; }
```
### GreenBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the band index for the green channel.</p>


```csharp
public int? GreenBandIndex { get; set; }
```
### MaxPercent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the maximum percent for the <xref href="ArcGIS.Core.CIM.RasterStretchType.PercentMinimumMaximum" data-throw-if-not-resolved="false"></xref> stretch type.</p>


```csharp
public double? MaxPercent { get; set; }
```
### MinPercent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the minimum percent for the <xref href="ArcGIS.Core.CIM.RasterStretchType.PercentMinimumMaximum" data-throw-if-not-resolved="false"></xref> stretch type.</p>


```csharp
public double? MinPercent { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the NoData color.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### RedBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the band index for the red channel.</p>


```csharp
public int? RedBandIndex { get; set; }
```
### StandardDeviationsParam

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the number of standard deviations for the <xref href="ArcGIS.Core.CIM.RasterStretchType.StandardDeviations" data-throw-if-not-resolved="false"></xref> stretch type.</p>


```csharp
public double? StandardDeviationsParam { get; set; }
```
### StretchType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RGBColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Core.CIM.RasterStretchType" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterStretchType? StretchType { get; set; }
```


