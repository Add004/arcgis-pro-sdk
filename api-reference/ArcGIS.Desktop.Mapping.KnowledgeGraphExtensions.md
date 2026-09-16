# KnowledgeGraphExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphExtensions.yml" sourcestartlinenumber="1">Contains extension methods to extend the <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>
and associated knowledge graph classes.</p>


## Object Signature

```csharp
public static class KnowledgeGraphExtensions
```


## Members

### ApplySchemaEdits(KnowledgeGraph, SchemaBuilder)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphExtensions.yml" sourcestartlinenumber="1">Addins should use the knowledge graph ApplySchemaEdits() call to execute enqueued
schema operations on <xref href="ArcGIS.Core.Data.DDL.SchemaBuilder" data-throw-if-not-resolved="false"></xref> rather than
<xref href="ArcGIS.Core.Data.DDL.SchemaBuilder.Build" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool ApplySchemaEdits(this KnowledgeGraph kg, SchemaBuilder schemaBuilder)
```


