# KnowledgeGraphValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphValue.yml" sourcestartlinenumber="1">Abstract base class for all kKnowledge graph values.</p>


## Object Signature

```csharp
public abstract class KnowledgeGraphValue : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphValue.yml" sourcestartlinenumber="1">Knowledge graph values are returned as the results of a
query or text search</p>


## Members

### KnowledgeGraphValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphValue.yml" sourcestartlinenumber="1">Only to be used by derived classes that support construction...</p>


```csharp
protected KnowledgeGraphValue()
```
### KnowledgeGraphValue(nint, KnowledgeGraphValueType, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphValue.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
protected KnowledgeGraphValue(nint valueHandle, KnowledgeGraphValueType valueType, SpatialReference spatialReference)
```
### KnowledgeGraphValueType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphValue.yml" sourcestartlinenumber="1">Gets the KnowledgeGraph value type.</p>


```csharp
public virtual KnowledgeGraphValueType KnowledgeGraphValueType { get; }
```


