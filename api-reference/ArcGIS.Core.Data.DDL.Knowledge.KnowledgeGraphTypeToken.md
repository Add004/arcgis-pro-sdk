# KnowledgeGraphTypeToken

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeToken.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.DDL.Token" data-throw-if-not-resolved="false"></xref> object to handle schema operations on a
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class KnowledgeGraphTypeToken : Token
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeToken.yml" sourcestartlinenumber="1">Users construct a <xref href="ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription" data-throw-if-not-resolved="false"></xref> containing the schema
for either an enity or relationship KnowledgeGraphNamedObjectType. When the KnowledgeGraphTypeDescription
instance is passed to a schema builder operation (such as Create, Modify, or Delete), a
a KnowledgeGraphTypeToken will be returned that contains the context for &quot;that&quot; given
operation which will be executed when a call to <xref href="ArcGIS.Core.Data.DDL.SchemaBuilder.Build" data-throw-if-not-resolved="false"></xref>
is made.</p>





