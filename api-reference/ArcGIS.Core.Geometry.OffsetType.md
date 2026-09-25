# OffsetType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.OffsetType.yml" sourcestartlinenumber="1">Offset options for use with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.Offset(ArcGIS.Core.Geometry.Geometry%2cSystem.Double%2cArcGIS.Core.Geometry.OffsetType%2cSystem.Double)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public enum OffsetType
```


## Members

### Bevel

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.OffsetType.yml" sourcestartlinenumber="1">Corners should be beveled - constructs the offset curve to be beveled about an obtuse angle.</p>


```csharp
Bevel = 4
```
### Miter

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.OffsetType.yml" sourcestartlinenumber="1">Corners should be mitered - constructs the offset curve to form a point about an obtuse angle.</p>


```csharp
Miter = 2
```
### Round

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.OffsetType.yml" sourcestartlinenumber="1">Corners should be rounded - constructs the offset curve to be rounded about an obtuse angle</p>


```csharp
Round = 8
```
### Square

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.OffsetType.yml" sourcestartlinenumber="1">Corners should be squared.</p>


```csharp
Square = 1
```


