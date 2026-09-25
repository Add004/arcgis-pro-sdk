# ElevationTypeDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Represents an elevation type definition.</p>


## Object Signature

```csharp
public class ElevationTypeDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Allows you to specify whether features display on the ground,
relative to the ground (for 3D layers only), at an absolute height, etc.
Once an elevation type definition is defined, call
<xref href="ArcGIS.Desktop.Mapping.Layer.SetElevationTypeDefinition(ArcGIS.Desktop.Mapping.ElevationTypeDefinition)?text=SetElevationTypeDefinition" data-throw-if-not-resolved="false"></xref>
to apply it.</p>


## Members

### ElevationTypeDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Represents an elevation type definition.</p>


```csharp
public ElevationTypeDefinition()
```
### CartographicOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Gets or sets the cartographic offset value.</p>


```csharp
public double? CartographicOffset { get; set; }
```
### CartographicOffsetUnits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Gets or sets the vertical units for the <xref href="ArcGIS.Desktop.Mapping.ElevationTypeDefinition.CartographicOffset" data-throw-if-not-resolved="false"></xref></p>


```csharp
public LinearUnit CartographicOffsetUnits { get; set; }
```
### CustomSurfaceURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Gets or sets the custom elevation surface URI.</p>


```csharp
public string CustomSurfaceURI { get; set; }
```
### ElevationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Desktop.Mapping.LayerElevationType?text=LayerElevationType" data-throw-if-not-resolved="false"></xref></p>


```csharp
public LayerElevationType ElevationType { get; set; }
```
### FeatureElevationExpression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Gets or sets the FeatureElevationExpression.</p>


```csharp
public string FeatureElevationExpression { get; set; }
```
### GeometryZValueExpressionString

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">VBScript feature elevation expression string to use for the feature geometry
z-value when specifying feature height.</p>


```csharp
public static readonly string GeometryZValueExpressionString
```
### NumericFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Gets or sets the NumericFieldName.</p>


```csharp
public string NumericFieldName { get; set; }
```
### VerticalExaggeration

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationTypeDefinition.yml" sourcestartlinenumber="1">Gets or sets the vertical exaggeration value.</p>


```csharp
public double? VerticalExaggeration { get; set; }
```


