# KnowledgeGraphPropertyInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Class representing information about the names of the unique identifier properties in a knowledge graph.
See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.GetPropertyNameInfo" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphPropertyInfo
```


## Members

### DestinationIDPropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the name of the graph property representing the Destination ID for relationship object types in a KnowledgeGraph.</p>


```csharp
public string DestinationIDPropertyName { get; }
```
### DocumentPropertyInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Knowledge.DocumentPropertyInfo" data-throw-if-not-resolved="false"></xref> if documents are supported.  If documents are not supported then this will be null.
See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.SupportsDocuments" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DocumentPropertyInfo DocumentPropertyInfo { get; }
```
### DocumentTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the knowledge graph document type name.</p>


```csharp
public string DocumentTypeName { get; }
```
### GlobalIDPropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the name of the graph property representing the Global ID for named object types in a KnowledgeGraph.</p>


```csharp
public string GlobalIDPropertyName { get; }
```
### HasDocumentTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the knowledge graph &quot;has document&quot; type name.</p>


```csharp
public string HasDocumentTypeName { get; }
```
### IDPropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the name of the graph property representing the ID for named object types in a KnowledgeGraph.</p>


```csharp
public string IDPropertyName { get; }
```
### OriginIDPropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the name of the graph property representing the Origin ID for relationship object types in a KnowledgeGraph.</p>


```csharp
public string OriginIDPropertyName { get; }
```
### ProvenancePropertyInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Knowledge.ProvenancePropertyInfo" data-throw-if-not-resolved="false"></xref> if provenance is supported.  If provenance is not supported then this will be null.
See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.SupportsProvenance" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ProvenancePropertyInfo ProvenancePropertyInfo { get; }
```
### ProvenanceTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets the knowledge graph provenance type name.</p>


```csharp
public string ProvenanceTypeName { get; }
```
### SupportsDocuments

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets if the knowledge graph supports documents.</p>


```csharp
public bool SupportsDocuments { get; }
```
### SupportsProvenance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets if the knowledge graph supports provenance.</p>


```csharp
public bool SupportsProvenance { get; }
```
### SupportsSearch

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Gets if the knowledge graph supports search.</p>


```csharp
public bool SupportsSearch { get; }
```


