# KnowledgeGraphIdentifierInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIdentifierInfo.yml" sourcestartlinenumber="1">Abstract base class representing information about unique identifiers
in the knowledge graph. Concrete subclasses include
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNativeIdentifier" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphUniformIdentifier" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class KnowledgeGraphIdentifierInfo : CoreObjectsBase, IDisposable
```


## Members

### GetIdentifierGeneration()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIdentifierInfo.yml" sourcestartlinenumber="1">Get an object with information regarding how the knowledge graph service
generates unique identifiers.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphIdentifierGeneration GetIdentifierGeneration()
```


