# AreaUnit

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Represents an area unit of measure.</p>


## Object Signature

```csharp
public sealed class AreaUnit : Unit
```

## Remarks

<p></p>
<p>The available area units of measure.</p>
<p></p>
<table>
  <tbody>
    <tr>
      <th>Factory Code</th>
      <th>Unit Name</th>
    </tr>
    <tr>
      <td>109401</td>
      <td>Square hectare</td>
    </tr>
    <tr>
      <td>109403</td>
      <td>US acre</td>
    </tr>
    <tr>
      <td>109404</td>
      <td>Square meter</td>
    </tr>
    <tr>
      <td>109405</td>
      <td>Square foot</td>
    </tr>
    <tr>
      <td>109414</td>
      <td>Square kilometer</td>
    </tr>
    <tr>
      <td>109439</td>
      <td>Square mile</td>
    </tr>
    <tr>
      <td>109442</td>
      <td>Square yard</td>
    </tr>
    <tr>
      <td>109450</td>
      <td>Square decimeter</td>
    </tr>
    <tr>
      <td>109451</td>
      <td>Square centimeter</td>
    </tr>
    <tr>
      <td>109452</td>
      <td>Square millimeter</td>
    </tr>
    <tr>
      <td>109453</td>
      <td>Square inch</td>
    </tr>
    <tr>
      <td>109463</td>
      <td>Square ares</td>
    </tr>
  </tbody>
</table>


## Members

### Acres

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in US acres (Factory Code = 109403).</p>


```csharp
public static AreaUnit Acres { get; }
```
### Ares

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in ares (Factory Code = 109463).</p>


```csharp
public static AreaUnit Ares { get; }
```
### ConvertFromSquareMeters(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Converts square meters to the unit of this instance.</p>


```csharp
public double ConvertFromSquareMeters(double squareMeters)
```
### ConvertTo(double, AreaUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Converts the area to the provided area unit.</p>


```csharp
public double ConvertTo(double inArea, AreaUnit outUnit)
```
### ConvertToSquareMeters(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Converts the area to square meters.</p>


```csharp
public double ConvertToSquareMeters(double area)
```
### CreateAreaUnit(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Convenience method to quickly create a <xref href="ArcGIS.Core.Geometry.AreaUnit" data-throw-if-not-resolved="false"></xref> instance.</p>


```csharp
public static AreaUnit CreateAreaUnit(int factoryCode)
```
### CreateAreaUnit(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.AreaUnit" data-throw-if-not-resolved="false"></xref> from well-known test. This method is useful for creating custom units.</p>


```csharp
public static AreaUnit CreateAreaUnit(string unitWkt)
```
### CreateAreaUnit(string, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Convenience method to quickly create a custom <xref href="ArcGIS.Core.Geometry.AreaUnit" data-throw-if-not-resolved="false"></xref> instance.</p>


```csharp
public static AreaUnit CreateAreaUnit(string name, double conversionFactor)
```
### Hectares

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in hectares (Factory Code = 109401).</p>


```csharp
public static AreaUnit Hectares { get; }
```
### SquareCentimeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square centimeters (Factory Code = 109451).</p>


```csharp
public static AreaUnit SquareCentimeters { get; }
```
### SquareDecimeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square decimeters (Factory Code = 109450).</p>


```csharp
public static AreaUnit SquareDecimeters { get; }
```
### SquareFeet

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square feet (Factory Code = 109405).</p>


```csharp
public static AreaUnit SquareFeet { get; }
```
### SquareInches

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square inches (Factory Code = 109453).</p>


```csharp
public static AreaUnit SquareInches { get; }
```
### SquareKilometers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square kilometers (Factory Code = 109414).</p>


```csharp
public static AreaUnit SquareKilometers { get; }
```
### SquareMeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square meters (Factory Code = 109404).</p>


```csharp
public static AreaUnit SquareMeters { get; }
```
### SquareMetersPerUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets the square meters per unit.</p>


```csharp
public double SquareMetersPerUnit { get; }
```
### SquareMiles

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square miles (Factory Code = 109439).</p>


```csharp
public static AreaUnit SquareMiles { get; }
```
### SquareMillimeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square millimeters (Factory Code = 109452).</p>


```csharp
public static AreaUnit SquareMillimeters { get; }
```
### SquareYards

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Gets an area unit object representing area in square yards (Factory Code = 109442).</p>


```csharp
public static AreaUnit SquareYards { get; }
```


