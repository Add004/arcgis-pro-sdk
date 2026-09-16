# Contingency

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Contingency.yml" sourcestartlinenumber="1">Represents the contingency constraints.</p>


## Object Signature

```csharp
public sealed class Contingency
```


## Members

### FieldGroup

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Contingency.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Contingency.FieldGroup" data-throw-if-not-resolved="false"></xref> to which this contingency is applied.</p>


```csharp
public FieldGroup FieldGroup { get; }
```
### GetContingentValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Contingency.yml" sourcestartlinenumber="1">Get the <xref href="ArcGIS.Core.Data.ContingentValue" data-throw-if-not-resolved="false"></xref>s by the <xref href="ArcGIS.Core.Data.FieldGroup.Name" data-throw-if-not-resolved="false"></xref></p>


```csharp
public IReadOnlyDictionary<string, ContingentValue> GetContingentValues()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Contingency.yml" sourcestartlinenumber="1">Gets the contingency's unique identifier.</p>


```csharp
public int ID { get; }
```
### IsRetired

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Contingency.yml" sourcestartlinenumber="1">Gets whether the contingency has been retired or not.</p>


```csharp
public bool IsRetired { get; }
```
### Subtype

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Contingency.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Contingency.Subtype" data-throw-if-not-resolved="false"></xref> to which this contingency is applied.</p>


```csharp
public Subtype Subtype { get; }
```


