# TableDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.TableDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class TableDescription : Description
```


## Members

### TableDescription(TableToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.TableDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TableDescription(TableToken tableToken)
```
### TableDescription(TableDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.TableDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TableDescription(TableDefinition tableDefinition)
```
### TableDescription(string, TableDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.TableDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TableDescription(string name, TableDefinition tableDefinition)
```
### TableDescription(string, IEnumerable&lt;FieldDescription&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.TableDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TableDescription(string name, IEnumerable<FieldDescription> fieldDescriptions)
```
### AliasName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.TableDescription.yml" sourcestartlinenumber="1">The alias name of the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string AliasName { get; set; }
```
### FieldDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.TableDescription.yml" sourcestartlinenumber="1">The list of <xref href="ArcGIS.Core.Data.DDL.FieldDescription" data-throw-if-not-resolved="false"></xref> items in the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<FieldDescription> FieldDescriptions { get; }
```
### SubtypeFieldDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.TableDescription.yml" sourcestartlinenumber="1">Denotes the subtype <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> in the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SubtypeFieldDescription SubtypeFieldDescription { get; set; }
```


