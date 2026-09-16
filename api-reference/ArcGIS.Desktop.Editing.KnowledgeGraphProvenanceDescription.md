# KnowledgeGraphProvenanceDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Represents the information in a knowledge graph provenance row.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphProvenanceDescription
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">A KnowledgeGraphProvenanceDescription is used to create provenance records
Provenance describes where information in the knowledge graph originates.  Each provenance record
associates the value stored in a property of an entity or a relationship with a specific source.
A property of an entity or a relationship can have many provenance records because many sources can
confirm the same piece of information.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="9">Once defined use <xref href="ArcGIS.Desktop.Editing.EditOperation.Create(ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription)" data-throw-if-not-resolved="false"></xref> to create a provenance record.</p>


## Members

### KnowledgeGraphProvenanceDescription(RowHandle, string, KnowledgeGraphSourceType, string, string, string, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Creates a new instance of a KnowledgeGraphProvenanceDescription.</p>


```csharp
public KnowledgeGraphProvenanceDescription(RowHandle rowHandle, string propertyName, KnowledgeGraphSourceType sourceType, string source, string sourceName = "", string comment = "", IReadOnlyDictionary<string, object> attributes = null)
```
### KnowledgeGraphProvenanceDescription(RowHandle, string, RowHandle, string, string, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Creates a new instance of a KnowledgeGraphProvenanceDescription.  Use this constructor for creating provenance records
where the Source Type will be set to <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphSourceType.Document" data-throw-if-not-resolved="false"></xref> and the document is specified using
a RowHandle of an existing row or a &quot;to be created&quot; row in the Document table.</p>


```csharp
public KnowledgeGraphProvenanceDescription(RowHandle rowHandle, string propertyName, RowHandle documentRowHandle, string sourceName = "", string comment = "", IReadOnlyDictionary<string, object> attributes = null)
```
### KnowledgeGraphProvenanceDescription(RowHandle, string, Guid, string, string, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Creates a new instance of a KnowledgeGraphProvenanceDescription.  Use this constructor for creating provenance records
where the Source Type will be set to <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphSourceType.Document" data-throw-if-not-resolved="false"></xref> and the document is specified using
a globalID of a row in the Document table.</p>


```csharp
public KnowledgeGraphProvenanceDescription(RowHandle rowHandle, string propertyName, Guid documentGuid, string sourceName = "", string comment = "", IReadOnlyDictionary<string, object> attributes = null)
```
### Attributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the additional attributes for user specified fields to assign to the row in the provenance table.</p>


```csharp
public IReadOnlyDictionary<string, object> Attributes { get; }
```
### Comment

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the comments about the source information. This is optional.</p>


```csharp
public string Comment { get; }
```
### DocumentGuid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the guid of a document row.  If <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.SourceType" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphSourceType.Document" data-throw-if-not-resolved="false"></xref> then the provenance document information
can be specified using the guid of a row in the Document table. Otherwise the value is null.</p>


```csharp
public Guid DocumentGuid { get; }
```
### DocumentRowHandle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the row handle of a document row.   If <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.SourceType" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphSourceType.Document" data-throw-if-not-resolved="false"></xref> then the provenance document information
can be specified using a RowHandle.  This row handle can be an existing row or a &quot;to be created&quot; row in the Document table.</p>


```csharp
public RowHandle DocumentRowHandle { get; }
```
### PropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the property name that this provenance record describes.</p>


```csharp
public string PropertyName { get; }
```
### RowHandle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the entity or relationship row that this provenance record describes.</p>


```csharp
public RowHandle RowHandle { get; }
```
### Source

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the source for the provenance information.  This could be a document filename (if <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.SourceType" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphSourceType.Document" data-throw-if-not-resolved="false"></xref>),
a URL or network file path if <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.SourceType" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphSourceType.URL" data-throw-if-not-resolved="false"></xref> or the source information itself
if <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.SourceType" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphSourceType.String" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string Source { get; }
```
### SourceName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the name for the source information.  This is optional.</p>


```csharp
public string SourceName { get; }
```
### SourceType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Gets the type of the source information.</p>


```csharp
public KnowledgeGraphSourceType SourceType { get; }
```


