# SubtypeFieldDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.SubtypeFieldDescription.yml" sourcestartlinenumber="1">Represents a mechanism to designate a <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> as the subtype field for a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class SubtypeFieldDescription : Description
```


## Members

### SubtypeFieldDescription(string, Dictionary&lt;int, string&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.SubtypeFieldDescription.yml" sourcestartlinenumber="1">Creates a description object of the subtype <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SubtypeFieldDescription(string subtypeFieldName, Dictionary<int, string> subtypes)
```
### DefaultSubtypeCode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.SubtypeFieldDescription.yml" sourcestartlinenumber="1">The code of the default subtype.</p>


```csharp
public int DefaultSubtypeCode { get; set; }
```
### Subtypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.SubtypeFieldDescription.yml" sourcestartlinenumber="1">The code-name pairs of all subtypes.</p>


```csharp
public Dictionary<int, string> Subtypes { get; }
```


