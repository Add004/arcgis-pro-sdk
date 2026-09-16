# KnowledgeGraphInvestigationProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationProjectItem.yml" sourcestartlinenumber="1">Represents a knowledge graph investigation project item.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphInvestigationProjectItem : KnowledgeGraphBaseProjectItem, IProjectItem, IMappableItem, IProjectItemRename, IProjectItemEdit, IPortalProjectItem
```


## Members

### CanOpenView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationProjectItem.yml" sourcestartlinenumber="1">Gets whether the view can be opened.</p>


```csharp
protected override bool CanOpenView()
```
### GetDatastore()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationProjectItem.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref> associated with the workspace corresponding to the
<xref href="ArcGIS.Desktop.Core.Item.Path" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraph GetDatastore()
```
### GetInvestigation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationProjectItem.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation?text=knowledge+graph+investigation" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphInvestigation GetInvestigation()
```
### OnFolderRename(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationProjectItem.yml" sourcestartlinenumber="1">Represents a knowledge graph investigation project item.</p>


```csharp
protected override void OnFolderRename(string oldValue, string newValue)
```
### OnRemoveFromProject()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationProjectItem.yml" sourcestartlinenumber="1">Call back whenever a project item is going to be removed from a project</p>


```csharp
public override void OnRemoveFromProject()
```
### OpenInvestigationPaneAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationProjectItem.yml" sourcestartlinenumber="1">Opens an investigation pane for the investigation project item</p>


```csharp
public Task<IKnowledgeGraphInvestigationPane> OpenInvestigationPaneAsync()
```


