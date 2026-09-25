# AngularUnit

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Represents an angular unit of measure used by a <xref href="ArcGIS.Core.Geometry.Geometry" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>, or in measurement conversion functions.</p>


## Object Signature

```csharp
public sealed class AngularUnit : Unit
```

## Remarks

<p></p>
<p>The available angular units of measure.</p>
<p></p>
<table>
  <tbody>
    <tr>
      <th>Factory Code</th>
      <th>Unit Name</th>
    </tr>
    <tr>
      <td>9101</td>
      <td>Radian</td>
    </tr>
    <tr>
      <td>9102</td>
      <td>Degree</td>
    </tr>
    <tr>
      <td>9103</td>
      <td>Arc-minute</td>
    </tr>
    <tr>
      <td>9104</td>
      <td>Arc-second</td>
    </tr>
    <tr>
      <td>9105</td>
      <td>Grad</td>
    </tr>
    <tr>
      <td>9106</td>
      <td>Gon</td>
    </tr>
    <tr>
      <td>9109</td>
      <td>Microradian</td>
    </tr>
    <tr>
      <td>9112</td>
      <td>Centesimal arc-minute</td>
    </tr>
    <tr>
      <td>9113</td>
      <td>Centesimal arc-second</td>
    </tr>
    <tr>
      <td>9114</td>
      <td>Mil</td>
    </tr>
    <tr>
      <td>909003</td>
      <td>DD (Decimal Degree)</td>
    </tr>
    <tr>
      <td>909004</td>
      <td>DMS (Degree Minute Second)</td>
    </tr>
    <tr>
      <td>909005</td>
      <td>DDM (Degree Decimal Minute)</td>
    </tr>
  </tbody>
</table>
<p></p>


## Members

### ConvertFromRadians(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Converts a radian angle to the unit of this instance.</p>


```csharp
public double ConvertFromRadians(double radians)
```
### ConvertTo(double, AngularUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Converts the angle to the provided angular unit.</p>


```csharp
public double ConvertTo(double inAngle, AngularUnit outUnit)
```
### ConvertToRadians(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Converts the angle to radians.</p>


```csharp
public double ConvertToRadians(double angle)
```
### CreateAngularUnit(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Convenience method to quickly create a <xref href="ArcGIS.Core.Geometry.AngularUnit" data-throw-if-not-resolved="false"></xref> instance using a factory code.</p>


```csharp
public static AngularUnit CreateAngularUnit(int factoryCode)
```
### CreateAngularUnit(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.AngularUnit" data-throw-if-not-resolved="false"></xref> instance from well-known text. This method is useful for creating a custom unit.</p>


```csharp
public static AngularUnit CreateAngularUnit(string unitWkt)
```
### CreateAngularUnit(string, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Convenience method to quickly create a custom <xref href="ArcGIS.Core.Geometry.AngularUnit" data-throw-if-not-resolved="false"></xref> instance.</p>


```csharp
public static AngularUnit CreateAngularUnit(string name, double conversionFactor)
```
### DecimalDegree

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing decimal degree (factory Code = 909003).</p>


```csharp
public static AngularUnit DecimalDegree { get; }
```
### DegreeDecimalMinute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing degree decimal minute (factory Code = 909005).</p>


```csharp
public static AngularUnit DegreeDecimalMinute { get; }
```
### DegreeMinuteSecond

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing degree minute second (factory Code = 909004).</p>


```csharp
public static AngularUnit DegreeMinuteSecond { get; }
```
### Degrees

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing angle in degrees (Factory Code = 9102). A degree is equal to PI/180 radians.</p>


```csharp
public static AngularUnit Degrees { get; }
```
### Gon

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing Gons (factory Code = 9106).</p>


```csharp
public static AngularUnit Gon { get; }
```
### Grads

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing angle in grads (Factory Code = 9105). Equivalent to one one-hundredth of a right-angle, a grad is equal to PI/200 radians. Also known as a gon.</p>


```csharp
public static AngularUnit Grads { get; }
```
### MicroRadian

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing MicroRadians (factory Code = 9109).</p>


```csharp
public static AngularUnit MicroRadian { get; }
```
### Mil6400

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing Mil6400 (factory Code = 9114).</p>


```csharp
public static AngularUnit Mil6400 { get; }
```
### MilliArcSecond

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing milli arc seconds (factory Code = 1031).</p>


```csharp
public static AngularUnit MilliArcSecond { get; }
```
### MinuteCentesimal

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing MinuteCentesimals (factory Code = 9112).</p>


```csharp
public static AngularUnit MinuteCentesimal { get; }
```
### Minutes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing angle in arc-minutes (Factory Code = 9103). An arc-minute is equal to 1/60th of a degree.</p>


```csharp
public static AngularUnit Minutes { get; }
```
### Radians

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing angle in radians (factory Code = 9101). A radian is an SI standard unit, equaling 180/PI degrees.</p>


```csharp
public static AngularUnit Radians { get; }
```
### RadiansPerUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets the radians per angular unit.</p>


```csharp
public double RadiansPerUnit { get; }
```
### SecondCentesimal

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing SecondCentesimals (factory Code = 9113).</p>


```csharp
public static AngularUnit SecondCentesimal { get; }
```
### Seconds

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Gets an angular unit object representing angle in arc-seconds (Factory Code = 9104). An arc-second is equal to 1/60th of an arc-minute.</p>


```csharp
public static AngularUnit Seconds { get; }
```


