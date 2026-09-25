# KnowledgeGraphInvestigationFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationFactory.yml" sourcestartlinenumber="1">Factory class to create new investigation project items.</p>


## Object Signature

```csharp
public class KnowledgeGraphInvestigationFactory : IKnowledgeGraphInvestigationFactory
```


## Members

### CreateInvestigation(CIMWorkspaceConnection, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationFactory.yml" sourcestartlinenumber="1">Creates a new KnowledgeGraphInvestigation in the project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphInvestigation CreateInvestigation(CIMWorkspaceConnection dataConnection, string name)
```
### CreateInvestigation(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationFactory.yml" sourcestartlinenumber="1">Creates a new KnowledgeGraphInvestigation in the project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphInvestigation CreateInvestigation(string knowledgeGraphServiceUri, string name)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for IKnowledgeGraphInvestigationFactory</p>


```csharp
public static IKnowledgeGraphInvestigationFactory Instance { get; }
```


