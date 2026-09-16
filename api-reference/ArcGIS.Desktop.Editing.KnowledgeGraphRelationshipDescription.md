# KnowledgeGraphRelationshipDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">Represents a relationship between two entities in a knowledge graph.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphRelationshipDescription : BaseRelationshipDescription
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">A KnowledgeGraphRelationshipDescription is used to create and delete a relationship between two rows defined by a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipType" data-throw-if-not-resolved="false"></xref>.
Once defined, use EditOperation.Create to create the relationship and EditOperation.Delete to remove the relationship.</p>


## Members

### KnowledgeGraphRelationshipDescription(RowHandle, RowHandle, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">Creates a new instance of the KnowledgeGraphRelationshipDescription class.</p>


```csharp
public KnowledgeGraphRelationshipDescription(RowHandle origin, RowHandle destination, IReadOnlyDictionary<string, object> attributes = null)
```
### KnowledgeGraphRelationshipDescription(RowHandle, Guid, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">Creates a new instance of the KnowledgeGraphRelationshipDescription class.</p>


```csharp
public KnowledgeGraphRelationshipDescription(RowHandle origin, Guid destination, IReadOnlyDictionary<string, object> attributes = null)
```
### KnowledgeGraphRelationshipDescription(Guid, RowHandle, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">Creates a new instance of the KnowledgeGraphRelationshipDescription class.</p>


```csharp
public KnowledgeGraphRelationshipDescription(Guid origin, RowHandle destination, IReadOnlyDictionary<string, object> attributes = null)
```
### KnowledgeGraphRelationshipDescription(Guid, Guid, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">Creates a new instance of the KnowledgeGraphRelationshipDescription class.</p>


```csharp
public KnowledgeGraphRelationshipDescription(Guid origin, Guid destination, IReadOnlyDictionary<string, object> attributes = null)
```
### DestinationGuid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">Gets the guid of the row in the destination table.</p>


```csharp
public Guid DestinationGuid { get; }
```
### OriginGuid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">Gets the guid of the row in the origin table.</p>


```csharp
public Guid OriginGuid { get; }
```


