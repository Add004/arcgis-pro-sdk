# KnowledgeGraphObjectValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphObjectValue.yml" sourcestartlinenumber="1">Represents an anonymous object value in a KnowledgeGraph.</p>


## Object Signature

```csharp
public class KnowledgeGraphObjectValue : KnowledgeGraphValue, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphObjectValue.yml" sourcestartlinenumber="1">This is the base class for <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectValue" data-throw-if-not-resolved="false"></xref>
which includes both entities and relationships</p>


## Members

### KnowledgeGraphObjectValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphObjectValue.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public KnowledgeGraphObjectValue()
```
### GetKeys()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphObjectValue.yml" sourcestartlinenumber="1">Gets the set of keys associated with the graph object value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual IReadOnlyList<string> GetKeys()
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphObjectValue.yml" sourcestartlinenumber="1">Gets and sets the value corresponding to the given key.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual object this[string key] { get; set; }
```


