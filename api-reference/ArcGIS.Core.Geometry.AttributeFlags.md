# AttributeFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.AttributeFlags.yml" sourcestartlinenumber="1">Flags used when creating a geometry in some GeometryBuilderEx methods specifying which attributes, Z, M, and ID, the
newly created geometry should have.
Use bitwise OR to specify more than one attribute. For example, to specify
that the geometry should have Z and M-values, specify AttributeFlags.HasZ | AttributeFlags.HasM.</p>


## Object Signature

```csharp
[Flags]
public enum AttributeFlags
```


## Members

### AllAttributes

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.AttributeFlags.yml" sourcestartlinenumber="1">Specifies that the geometry has Z, M and ID-values.</p>


```csharp
AllAttributes = HasZ | HasM | HasID
```
### HasID

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.AttributeFlags.yml" sourcestartlinenumber="1">Specifies that the geometry has ID-values.</p>


```csharp
HasID = 4
```
### HasM

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.AttributeFlags.yml" sourcestartlinenumber="1">Specified that the geometry has M-values.</p>


```csharp
HasM = 2
```
### HasZ

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.AttributeFlags.yml" sourcestartlinenumber="1">Specifies that the geometry has Z-values.</p>


```csharp
HasZ = 1
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.AttributeFlags.yml" sourcestartlinenumber="1">Specifies that the geometry has no attributes. It does not have Z, M or ID-values.</p>


```csharp
None = 0
```


