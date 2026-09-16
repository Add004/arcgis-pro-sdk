# KnowledgeGraphEndPoint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphEndPoint.yml" sourcestartlinenumber="1">Represents an end point for a relationship type in the data model.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphEndPoint : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphEndPoint.yml" sourcestartlinenumber="1">An end point consists of an origin entity type and a
destination entity type.</p>


## Members

### GetDestinationEntityTypeName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphEndPoint.yml" sourcestartlinenumber="1">Get the destination entity type name for the end point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetDestinationEntityTypeName()
```
### GetOriginEntityTypeName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphEndPoint.yml" sourcestartlinenumber="1">Get the origin entity type name for the end point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetOriginEntityTypeName()
```


