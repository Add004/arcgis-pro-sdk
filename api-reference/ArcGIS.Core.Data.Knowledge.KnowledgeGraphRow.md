# KnowledgeGraphRow

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRow.yml" sourcestartlinenumber="1">Represents a row from a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class KnowledgeGraphRow : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRow.yml" sourcestartlinenumber="1">KnowledgeGraphRows are returned from querying a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### GetCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRow.yml" sourcestartlinenumber="1">Gets the count of values on the <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphRow" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ulong GetCount()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRow.yml" sourcestartlinenumber="1">Gets the value in the graph row specified by the index.
This indexer must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[int index] { get; }
```


