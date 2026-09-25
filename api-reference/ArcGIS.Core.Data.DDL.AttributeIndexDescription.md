# AttributeIndexDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributeIndexDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create an attribute <xref href="ArcGIS.Core.Data.Index" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AttributeIndexDescription : IndexDescription
```


## Members

### AttributeIndexDescription(Index, TableDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributeIndexDescription.yml" sourcestartlinenumber="1">Creates a description object of the attribute <xref href="ArcGIS.Core.Data.Index" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AttributeIndexDescription(Index attributeIndex, TableDescription tableDescription)
```
### AttributeIndexDescription(string, TableDescription, IEnumerable&lt;string&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributeIndexDescription.yml" sourcestartlinenumber="1">Creates a description object of the attribute <xref href="ArcGIS.Core.Data.Index" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AttributeIndexDescription(string indexName, TableDescription tableDescription, IEnumerable<string> indexFieldNames)
```
### FieldNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributeIndexDescription.yml" sourcestartlinenumber="1">The list of field names in the TableDescription that will be present in the attribute index.</p>


```csharp
public IReadOnlyList<string> FieldNames { get; }
```
### IsAscending

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributeIndexDescription.yml" sourcestartlinenumber="1">Indicates whether or not the attribute index is based on ascending order.</p>


```csharp
public bool IsAscending { get; init; }
```
### IsUnique

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributeIndexDescription.yml" sourcestartlinenumber="1">Indicates whether or not the attribute index is unique.</p>


```csharp
public bool IsUnique { get; init; }
```
### TableDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributeIndexDescription.yml" sourcestartlinenumber="1">The description object representing the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> that will hold the attribute index.</p>


```csharp
public TableDescription TableDescription { get; }
```


