# VectorFieldColorizerDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorFieldColorizerDefinition.yml" sourcestartlinenumber="1">Represents a colorizer definition for a Vector Field colorizer that enables you to use a magnitude and direction component, or a U and V component to display your data.</p>


## Object Signature

```csharp
public class VectorFieldColorizerDefinition : RasterColorizerDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorFieldColorizerDefinition.yml" sourcestartlinenumber="1">VectorFieldColorizerDefinition class allows you to define a simplified list of parameters to create a Vector Field colorizer.<br>
Once you define a Vector Field colorizer definition, you can call the <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.CreateColorizer(ArcGIS.Desktop.Mapping.RasterColorizerDefinition)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.SetColorizer(ArcGIS.Core.CIM.CIMRasterColorizer)" data-throw-if-not-resolved="false"></xref> methods to create and assign a Vector Field colorizer to a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### VectorFieldColorizerDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorFieldColorizerDefinition.yml" sourcestartlinenumber="1">Creates a default Vector Field colorizer definition.</p>


```csharp
public VectorFieldColorizerDefinition()
```
### VectorFieldColorizerDefinition(int, int, bool, SymbolizationType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorFieldColorizerDefinition.yml" sourcestartlinenumber="1">Creates a Vector Field colorizer definition with parameters.</p>


```csharp
public VectorFieldColorizerDefinition(int magnitudeBandIndex, int directionBandIndex, bool isUVComponents = false, SymbolizationType symbolizationType = 1)
```
### DirectionBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorFieldColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the direction band index.</p>


```csharp
public int? DirectionBandIndex { get; set; }
```
### IsUVComponents

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorFieldColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean value indicating whether the flow is composed from U and V components.</p>


```csharp
public bool? IsUVComponents { get; set; }
```
### MagnitudeBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorFieldColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the magnitude band index.</p>


```csharp
public int? MagnitudeBandIndex { get; set; }
```
### TheSymbolizationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorFieldColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Core.CIM.SymbolizationType" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SymbolizationType? TheSymbolizationType { get; set; }
```


