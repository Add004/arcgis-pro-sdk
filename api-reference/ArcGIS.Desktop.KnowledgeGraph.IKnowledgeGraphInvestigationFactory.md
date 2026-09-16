# IKnowledgeGraphInvestigationFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphInvestigationFactory.yml" sourcestartlinenumber="1">Provides access to investigation creation members.</p>


## Object Signature

```csharp
public interface IKnowledgeGraphInvestigationFactory
```


## Members

### CreateInvestigation(CIMWorkspaceConnection, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphInvestigationFactory.yml" sourcestartlinenumber="1">Creates a new KnowledgeGraphInvestigation in the project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
KnowledgeGraphInvestigation CreateInvestigation(CIMWorkspaceConnection dataConnection, string name)
```
### CreateInvestigation(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphInvestigationFactory.yml" sourcestartlinenumber="1">Creates a new KnowledgeGraphInvestigation in the project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
KnowledgeGraphInvestigation CreateInvestigation(string knowledgeGraphServiceUri, string name)
```


