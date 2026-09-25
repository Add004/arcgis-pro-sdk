# GeometricEffectOffsetMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectOffsetMethod.yml" sourcestartlinenumber="1">Geometric effect offset method which specifies the way the strokes or fills are displayed at corners.</p>


## Object Signature

```csharp
public enum GeometricEffectOffsetMethod
```


## Members

### Bevelled

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectOffsetMethod.yml" sourcestartlinenumber="1">Bevelled - follows the shortest straight path across a corner of the line or polygon.</p>


```csharp
Bevelled = 1
```
### Mitered

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectOffsetMethod.yml" sourcestartlinenumber="1">Mitered - matches the exact shape around a corner of the line or polygon.</p>


```csharp
Mitered = 0
```
### Rounded

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectOffsetMethod.yml" sourcestartlinenumber="1">Rounded - follows a path of equal distance around a corner of the line or polygon.</p>


```csharp
Rounded = 2
```
### Square

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectOffsetMethod.yml" sourcestartlinenumber="1">Square - follows a straight path across the corner of a line or polygon.</p>


```csharp
Square = 3
```


