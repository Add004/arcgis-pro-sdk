# KnowledgeGraphConnectionProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphConnectionProperties.yml" sourcestartlinenumber="1">Represents the properties used to connect to a knowledge graph datastore.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphConnectionProperties : Connector
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphConnectionProperties.yml" sourcestartlinenumber="1">Knowledge graphs can use either a service url to a knowledge graph
service or path to a file-based knowledge graph</p>


## Members

### KnowledgeGraphConnectionProperties(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphConnectionProperties.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>KnowledgeGraphConnectionProperties</code> class.</p>


```csharp
public KnowledgeGraphConnectionProperties(Uri pathOrserviceURL)
```
### PathOrURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphConnectionProperties.yml" sourcestartlinenumber="1">Gets the path or service URL.</p>


```csharp
public Uri PathOrURL { get; }
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphConnectionProperties.yml" sourcestartlinenumber="1">Get the service URL.</p>


```csharp
[Obsolete("This property is deprecated and will be removed at 4.0. Please use 'PathOrURL' instead")]
public Uri URL { get; }
```


