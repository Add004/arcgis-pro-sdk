# KnowledgeGraphLayerException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphLayerException.yml" sourcestartlinenumber="1">Managed exception base class for custom <xref href="ArcGIS.Desktop.Mapping.KnowledgeGraphLayer" data-throw-if-not-resolved="false"></xref> exceptions</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphLayerException : KnowledgeGraphException, ISerializable
```


## Members

### InvalidNamedTypes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphLayerException.yml" sourcestartlinenumber="1">Gets a list of the invalid type names provided to the layer create or append</p>


```csharp
public IReadOnlyList<string> InvalidNamedTypes { get; }
```


