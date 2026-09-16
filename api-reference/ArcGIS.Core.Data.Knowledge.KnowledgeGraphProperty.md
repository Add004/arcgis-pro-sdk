# KnowledgeGraphProperty

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty.yml" sourcestartlinenumber="1">Represents a knowledge graph property.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphProperty : Field, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty.yml" sourcestartlinenumber="1">Properties can contain either a primitive value (such as
ints, doubles, strings, dates, etc) or a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphValue" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### GetHasDefaultVisibility()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty.yml" sourcestartlinenumber="1">Gets a boolean indicating whether a graph property is visible by default.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetHasDefaultVisibility()
```
### GetIsSystemMaintained()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty.yml" sourcestartlinenumber="1">Gets a boolean indicating whether a graph property is system maintained.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsSystemMaintained()
```
### GetRole()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyRole" data-throw-if-not-resolved="false"></xref> indicating
the role of the graph property.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphPropertyRole GetRole()
```


