# FieldGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.FieldGroup.yml" sourcestartlinenumber="1">Represents a field group within a <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class FieldGroup
```


## Members

### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FieldGroup.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### FieldNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FieldGroup.yml" sourcestartlinenumber="1">Gets the list of names of the fields that support contingent values.</p>


```csharp
public IReadOnlyList<string> FieldNames { get; }
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FieldGroup.yml" sourcestartlinenumber="1">Obtains a hash code of the object. Used in Equals.</p>


```csharp
public override int GetHashCode()
```
### IsRestrictive

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FieldGroup.yml" sourcestartlinenumber="1">Gets whether the <xref href="ArcGIS.Core.Data.FieldGroup" data-throw-if-not-resolved="false"></xref> is restrictive.</p>


```csharp
public bool IsRestrictive { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FieldGroup.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FieldGroup" data-throw-if-not-resolved="false"></xref> name.</p>


```csharp
public string Name { get; }
```


