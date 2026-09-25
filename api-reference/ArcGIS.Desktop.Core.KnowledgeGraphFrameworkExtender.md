# KnowledgeGraphFrameworkExtender

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.Core.KnowledgeGraphFrameworkExtender.yml" sourcestartlinenumber="1">Contains extension methods to extend ArcGIS.Desktop.Framework members.</p>


## Object Signature

```csharp
public static class KnowledgeGraphFrameworkExtender
```


## Members

### CreateDataModelPaneAsync(PaneCollection, KnowledgeGraphInvestigation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.KnowledgeGraphFrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new knowledge graph data model pane using a knowledge graph investigation.</p>


```csharp
public static Task<IKnowledgeGraphDataModelPane> CreateDataModelPaneAsync(this PaneCollection paneCollection, KnowledgeGraphInvestigation investigation)
```
### CreateInvestigationPaneAsync(PaneCollection, KnowledgeGraphInvestigation, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.KnowledgeGraphFrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new knowledge graph investigation pane using a knowledge graph investigation.</p>


```csharp
public static Task<IKnowledgeGraphInvestigationPane> CreateInvestigationPaneAsync(this PaneCollection paneCollection, KnowledgeGraphInvestigation investigation, KnowledgeGraphLayerIDSet idSet = null)
```


