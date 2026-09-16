# IKnowledgeGraphDataModelPane

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphDataModelPane.yml" sourcestartlinenumber="1">Represents a pane which contains a Knowledge Graph data model view.</p>


## Object Signature

```csharp
public interface IKnowledgeGraphDataModelPane
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphDataModelPane.yml" sourcestartlinenumber="1">Gets or sets the caption for the pane.</p>


```csharp
string Caption { get; set; }
```
### DataModelView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphDataModelPane.yml" sourcestartlinenumber="1">Gets the Knowledge Graph data model view contained within the pane.</p>


```csharp
KnowledgeGraphDataModelView DataModelView { get; }
```
### ViewState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphDataModelPane.yml" sourcestartlinenumber="1">Gets the definition of the view within the pane.</p>


```csharp
CIMView ViewState { get; }
```


