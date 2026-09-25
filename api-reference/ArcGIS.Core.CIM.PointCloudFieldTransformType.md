# PointCloudFieldTransformType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.PointCloudFieldTransformType.yml" sourcestartlinenumber="1">Point cloud field transform types.</p>


## Object Signature

```csharp
public enum PointCloudFieldTransformType
```


## Members

### AbsoluteValue

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PointCloudFieldTransformType.yml" sourcestartlinenumber="1">Apply abs() to field values.</p>


```csharp
AbsoluteValue = 3
```
### HighFourBit

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PointCloudFieldTransformType.yml" sourcestartlinenumber="1">Bitwise shift field values to the right by 4.</p>


```csharp
HighFourBit = 2
```
### LowFourBit

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PointCloudFieldTransformType.yml" sourcestartlinenumber="1">Apply 0xF mask to field values.</p>


```csharp
LowFourBit = 1
```
### ModuloTen

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PointCloudFieldTransformType.yml" sourcestartlinenumber="1">Modulate field values by 10.</p>


```csharp
ModuloTen = 4
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PointCloudFieldTransformType.yml" sourcestartlinenumber="1">Do not transform field values.</p>


```csharp
None = 0
```


