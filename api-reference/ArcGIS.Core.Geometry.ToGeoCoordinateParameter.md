# ToGeoCoordinateParameter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">A class used as the parameter to <xref href="ArcGIS.Core.Geometry.MapPoint.ToGeoCoordinateString(ArcGIS.Core.Geometry.ToGeoCoordinateParameter)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ToGeoCoordinateParameter
```


## Members

### ToGeoCoordinateParameter(GeoCoordinateType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">Create a new instance of ToGeoCoordinateParameter with the given string notation.</p>


```csharp
public ToGeoCoordinateParameter(GeoCoordinateType geoCoordType)
```
### ToGeoCoordinateParameter(GeoCoordinateType, ToGeoCoordinateMode)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">Create a new instance of ToGeoCoordinateParameter with the given string notation and format.</p>


```csharp
public ToGeoCoordinateParameter(GeoCoordinateType geoCoordType, ToGeoCoordinateMode geoCoordMode)
```
### ToGeoCoordinateParameter(GeoCoordinateType, ToGeoCoordinateMode, int, bool, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">Create a new instance of ToGeoCoordinateParameter with the given parameters.</p>


```csharp
public ToGeoCoordinateParameter(GeoCoordinateType geoCoordType, ToGeoCoordinateMode geoCoordMode, int numDigits, bool rounding, bool addSpaces)
```
### AddSpaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">Optional. The AddSpaces value applies only to types USNG and UTM.
The default value is true.</p>


```csharp
public bool AddSpaces { get; set; }
```
### GeoCoordinateMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">Optional. The non-default conversion options for MGRS and UTM string types.</p>


```csharp
public ToGeoCoordinateMode GeoCoordinateMode { get; set; }
```
### GeoCoordinateType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">The type of string to which the point will be converted.</p>


```csharp
public GeoCoordinateType GeoCoordinateType { get; set; }
```
### NumDigits

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">Optional. The number of digits to output for each of the numerical portions in the string.
The default value varies depending on the GeoCoordinateType.</p>
<table><thead><tr><th class="term">GeoCoordinateType</th><th class="description">NumDigits</th></tr></thead><tbody><tr><td class="term">MGRS</td><td class="description">5</td></tr><tr><td class="term">USNG</td><td class="description">8</td></tr><tr><td class="term">UTM</td><td class="description">NA</td></tr><tr><td class="term">GeoRef</td><td class="description">5</td></tr><tr><td class="term">GARS</td><td class="description">NA</td></tr><tr><td class="term">DMS</td><td class="description">2</td></tr><tr><td class="term">DDM</td><td class="description">4</td></tr><tr><td class="term">DD</td><td class="description">6</td></tr></tbody></table>


```csharp
public int NumDigits { get; set; }
```
### Reset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">Resets all values except <xref href="ArcGIS.Core.Geometry.ToGeoCoordinateParameter.GeoCoordinateType" data-throw-if-not-resolved="false"></xref> to the default values.</p>


```csharp
public void Reset()
```
### Round

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">Optional. The Round value applies only to types MGRS, USNG, and GeoRef.
If true, then numeric portions of the string are rounded to the nearest whole
magnitude as specified by NumDigits. Otherwise, numeric portions
of the string are truncated. The default value is true.</p>


```csharp
public bool Round { get; set; }
```


