# KnowledgeGraphPrimitiveValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPrimitiveValue.yml" sourcestartlinenumber="1">Represents a primitive value in a KnowledgeGraph.</p>


## Object Signature

```csharp
public class KnowledgeGraphPrimitiveValue : KnowledgeGraphValue, IDisposable
```


## Members

### GetValue()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPrimitiveValue.yml" sourcestartlinenumber="1">Gets the underlying value associated with the <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphPrimitiveValue" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetValue()
```


