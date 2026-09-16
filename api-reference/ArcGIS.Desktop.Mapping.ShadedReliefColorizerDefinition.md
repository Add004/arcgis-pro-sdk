# ShadedReliefColorizerDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Represents a colorizer definition for a ShadedRelief colorizer that enables you to display your dataset with a color 3D representation created by merging the images from the elevation-coded and hillshade methods. It uses the altitude and azimuth properties to specify the sun's position.</p>


## Object Signature

```csharp
public class ShadedReliefColorizerDefinition : RasterColorizerDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">ShadedReliefColorizerDefinition class allows you to define a simplified list of parameters to create a ShadedRelief colorizer.<br>
Once you define a ShadedRelief colorizer definition, you can call the <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.CreateColorizer(ArcGIS.Desktop.Mapping.RasterColorizerDefinition)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.SetColorizer(ArcGIS.Core.CIM.CIMRasterColorizer)" data-throw-if-not-resolved="false"></xref> methods to create and assign a ShadedRelief colorizer to a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### ShadedReliefColorizerDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Creates a default ShadedRelief colorizer definition.</p>


```csharp
public ShadedReliefColorizerDefinition()
```
### ShadedReliefColorizerDefinition(double, double, double, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Creates a ShadedRelief colorizer definition with parameters.</p>


```csharp
public ShadedReliefColorizerDefinition(double zFactor, double altitude, double azimuth, CIMColorRamp colorRamp = null)
```
### ShadedReliefColorizerDefinition(double, double, double, CIMColorRamp, ColorizerHillshadeType, ColorizerScalingType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Creates a ShadedRelief colorizer definition with parameters.</p>


```csharp
public ShadedReliefColorizerDefinition(double zFactor, double altitude, double azimuth, CIMColorRamp colorRamp = null, ColorizerHillshadeType hillshadeType = 0, ColorizerScalingType scalingType = 0)
```
### Altitude

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets altitude. The value will be ignored if UseMapIlluminationProperties is set to true.</p>


```csharp
public double? Altitude { get; set; }
```
### Azimuth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets azimuth. The value will be ignored if UseMapIlluminationProperties is set to true.</p>


```csharp
public double? Azimuth { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### HillShadeType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets or sets the hillshade type.</p>


```csharp
public ColorizerHillshadeType? HillShadeType { get; set; }
```
### PixelSizeFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets pixel size factor.</p>


```csharp
public double? PixelSizeFactor { get; set; }
```
### PixelSizePower

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets pixel size power.</p>


```csharp
public double? PixelSizePower { get; set; }
```
### RemoveEdgeEffect

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to remove edge effect.</p>


```csharp
public bool? RemoveEdgeEffect { get; set; }
```
### ScalingType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets or sets the scaling type.</p>


```csharp
public ColorizerScalingType? ScalingType { get; set; }
```
### UseMapIlluminationProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use map level illumination properties of altitude and azimuth.</p>


```csharp
public bool? UseMapIlluminationProperties { get; set; }
```
### ZFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ShadedReliefColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets z scale factor.</p>


```csharp
public double? ZFactor { get; set; }
```


