# WktFormatMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">The format mode for <xref href="ArcGIS.Core.Geometry.SpatialReference.GetWkt2(ArcGIS.Core.Geometry.WktFormatMode)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Geometry.SpatialReferenceBuilder.GetWkt2(ArcGIS.Core.Geometry.WktFormatMode)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum WktFormatMode
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">When authority is included in the string it will look something like &quot;ID[&quot;EPSG&quot;,4269]&quot; or &quot;ID[&quot;Esri&quot;,54004]&quot;.</p>


## Members

### AuthorityAll

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Include authority in all objects</p>


```csharp
AuthorityAll = 2
```
### AuthorityTop

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Include authority in top-level objects only</p>


```csharp
AuthorityTop = 1
```
### AuthorityVersion

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Include authority version</p>


```csharp
AuthorityVersion = 4
```
### DisplayNameAll

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Include display name in all objects</p>


```csharp
DisplayNameAll = 32
```
### DisplayNameTop

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Include display name in top-level objects</p>


```csharp
DisplayNameTop = 16
```
### FormattedWithSpaces

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Multiple line with space indents</p>


```csharp
FormattedWithSpaces = 256
```
### FormattedWithTabs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Multiple line with tab indents</p>


```csharp
FormattedWithTabs = 512
```
### LegacyPrecision

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Use 16-digit precision for doubles. Default is 17-digit precision.</p>


```csharp
LegacyPrecision = 33554432
```
### NoMetadata

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">Exclude metadata from string</p>


```csharp
NoMetadata = 32768
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">No authority is included</p>


```csharp
None = 0
```


