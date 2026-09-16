# RulePackageDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageDescription.yml" sourcestartlinenumber="1">Contains the attributes and characteristics of a Rule package.</p>


## Object Signature

```csharp
public sealed class RulePackageDescription : IReadOnlyCollection<RulePackageAttribute>, IEnumerable<RulePackageAttribute>, IEnumerable, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageDescription.yml" sourcestartlinenumber="1">Enumerate (&quot;i.e. foreach ) on the description to retrieve the attributes or use
an index to access a particular attribute directly.</p>


## Members

### Count

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageDescription.yml" sourcestartlinenumber="1">Gets the count of attributes in the package description</p>


```csharp
public int Count { get; }
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageDescription.yml" sourcestartlinenumber="1">Implements IDisposable</p>


```csharp
public void Dispose()
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.esriGeometryType" data-throw-if-not-resolved="false"></xref> of the rule package</p>


```csharp
public esriGeometryType GeometryType { get; }
```
### GetEnumerator()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageDescription.yml" sourcestartlinenumber="1">Returns an enumerator that iterates through a collection.</p>


```csharp
public IEnumerator<RulePackageAttribute> GetEnumerator()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageDescription.yml" sourcestartlinenumber="1">Gets the RulePackageAttribute at the specified index.</p>


```csharp
public RulePackageAttribute this[int index] { get; }
```
### RulePackage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageDescription.yml" sourcestartlinenumber="1">Gets the rule package for this description</p>


```csharp
public string RulePackage { get; }
```


