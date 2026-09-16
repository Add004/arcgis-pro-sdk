# KnowledgeGraphDocumentDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Represents a document row in a knowledge graph.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphDocumentDescription
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">A KnowledgeGraphDocumentDescription is used to create a row in the Knowledge Graph document table.
Once defined, use <xref href="ArcGIS.Desktop.Editing.EditOperation.Create(ArcGIS.Desktop.Mapping.MapMember%2cArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription)" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Desktop.Editing.EditOperation.Create(ArcGIS.Core.Data.Table%2cArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription)" data-throw-if-not-resolved="false"></xref> to create the row.
The Create method will auto-populate the Url, Name, FileExtension and contentType fields of the document row
from the path supplied.<br>
Use the <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.Text" data-throw-if-not-resolved="false"></xref> property in the KnowledgeGraphDocumentDescription to
specify custom text. If no value is supplied and text can be extracted from the document (for example a .txt file),
then the Text field will be auto-populated with this extracted value.
Specify values for the <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.Title" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.Keywords" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.Metadata" data-throw-if-not-resolved="false"></xref>
properties to populate values in those fields when the row is created.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="14">The Create operations return a <xref href="ArcGIS.Desktop.Editing.RowToken" data-throw-if-not-resolved="false"></xref> - a representation of the future or &quot;to be&quot; created row.
Create a <xref href="ArcGIS.Desktop.Editing.RowHandle" data-throw-if-not-resolved="false"></xref> with this rowToken and use with a <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription" data-throw-if-not-resolved="false"></xref>
to create the relationship between an entity and the document row.</p>


## Members

### KnowledgeGraphDocumentDescription(Geometry, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Creates a new instance of a KnowledgeGraphDocumentDescription.</p>


```csharp
public KnowledgeGraphDocumentDescription(Geometry geometry = null, IReadOnlyDictionary<string, object> attributes = null)
```
### KnowledgeGraphDocumentDescription(string, Geometry, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Creates a new instance of a KnowledgeGraphDocumentDescription.</p>


```csharp
public KnowledgeGraphDocumentDescription(string path, Geometry geometry = null, IReadOnlyDictionary<string, object> attributes = null)
```
### Attributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Gets the additional attributes for user specified fields to assign to the new row in the document table.</p>


```csharp
public IReadOnlyDictionary<string, object> Attributes { get; }
```
### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Gets the geometry for the document row.</p>


```csharp
public Geometry Geometry { get; }
```
### Keywords

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Gets and sets the keywords for the document row.</p>


```csharp
public string Keywords { get; set; }
```
### Metadata

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Gets and sets the metadata for the document row.</p>


```csharp
public string Metadata { get; set; }
```
### Text

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Gets and sets the text for the document row.</p>


```csharp
public string Text { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Gets and sets the title for the document row.</p>


```csharp
public string Title { get; set; }
```
### Url

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Gets the location of the document.  This can be a file path or a URL.</p>


```csharp
public string Url { get; }
```


