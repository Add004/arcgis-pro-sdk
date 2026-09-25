# KnowledgeGraphQueryFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Represents a filter for performing a query against a
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class KnowledgeGraphQueryFilter
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Refer to <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.SubmitQuery(ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter)" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### KnowledgeGraphQueryFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Represents a filter for performing a query against a
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphQueryFilter()
```
### BindParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Gets the query bind parameter collection. The collection is a
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphObjectValue" data-throw-if-not-resolved="false"></xref>. This property must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphObjectValue BindParameters { get; }
```
### Default

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Gets the default KnowledgeGraphQueryFilter.</p>


```csharp
public static KnowledgeGraphQueryFilter Default { get; }
```
### DefaultQueryText

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">The default query text string if none is provided.</p>


```csharp
public static readonly string DefaultQueryText
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Gets the query id.</p>


```csharp
public int ID { get; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Gets or sets the spatial reference to be applied to any
returned geometries.</p>


```csharp
public SpatialReference OutputSpatialReference { get; set; }
```
### ProvenanceBehavior

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Indicates whether entities with an entity type of role
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectTypeRole.Provenance" data-throw-if-not-resolved="false"></xref>
should be excluded or included in the query results.  Default value is <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProvenanceBehavior.Exclude" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphProvenanceBehavior ProvenanceBehavior { get; set; }
```
### QueryText

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Gets or sets the query string to be used to filter the returned rows.</p>


```csharp
public string QueryText { get; set; }
```


