# IKnowledgeGraphInvestigationPane

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphInvestigationPane.yml" sourcestartlinenumber="1">Represents a pane which contains a Knowledge Graph investigation view. See <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public interface IKnowledgeGraphInvestigationPane
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphInvestigationPane.yml" sourcestartlinenumber="1">Gets or sets the caption for the pane.</p>


```csharp
string Caption { get; set; }
```
### InvestigationView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphInvestigationPane.yml" sourcestartlinenumber="1">Gets the Knowledge Graph investigation view contained within the pane.</p>


```csharp
KnowledgeGraphInvestigationView InvestigationView { get; }
```
### ViewState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.IKnowledgeGraphInvestigationPane.yml" sourcestartlinenumber="1">Gets the definition of the view within the pane.</p>


```csharp
CIMView ViewState { get; }
```


