# KnowledgeGraphInvestigationView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Represents the view of a Knowledge Graph investigation in a pane.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphInvestigationView
```

## Remarks

<p>
    A project can contain multiple investigations.  An investigation view is simply a view of an investigation. 
    The KnowledgeGraphInvestigationView class provides methods and properties to navigate and interact with items in the investigation. 
    The investigation being visualized in the view can be accessed via the <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.Investigation" data-throw-if-not-resolved="false"></xref> property.
    </p>
<p>
    There can be multiple investigation views open at a given time, but there can only be one active investigation view.
    The active investigation view will set the context for the ribbon and many of the dock panes in the application.
    For example, the Contents pane will reflect the items of the active investigation view's investigation.
    The instance of the active investigation view can be accessed via the static the <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.Active" data-throw-if-not-resolved="false"></xref> property. 
    The property will return null if there is no active investigation view.
    </p>
<p>
    The investigation view also provides the context for managing selected items in the Contents pane.  
    For example, the <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.GetSelectedEntities" data-throw-if-not-resolved="false"></xref> method returns a collection of entities that
    are currently selected in the Contents pane.
    </p>


## Members

### Active

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Gets the active Knowledge Graph investigation view.</p>


```csharp
public static KnowledgeGraphInvestigationView Active { get; }
```
### ClearSelectedRecords()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Clear the selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearSelectedRecords()
```
### ClearTOCSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Clears the selection from the TOC.</p>


```csharp
public void ClearTOCSelection()
```
### GetSearchOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Gets the set of search options for the Knowledge Graph investigation view.</p>


```csharp
public SearchOptions GetSearchOptions()
```
### GetSelectedEntities()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Gets the collection of entity types selected in the TOC.</p>


```csharp
public IReadOnlyList<string> GetSelectedEntities()
```
### GetSelectedRecords()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Gets the selected records. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphLayerIDSet GetSelectedRecords()
```
### GetSelectedRelationships()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Gets the collection of relationship types selected in the TOC.</p>


```csharp
public IReadOnlyList<string> GetSelectedRelationships()
```
### Investigation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Gets the Knowledge Graph investigation associated with the investigation view.</p>


```csharp
public KnowledgeGraphInvestigation Investigation { get; }
```
### IsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Gets a value that indicates whether the KnowledgeGraphInvestigationView can be accessed.
This property is <code>false</code> while the investigation view processes major operations like initializing.</p>


```csharp
public bool IsReady { get; }
```
### SelectEntities(IReadOnlyCollection&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Selects entity types in the TOC.</p>


```csharp
public void SelectEntities(IReadOnlyCollection<string> entities)
```
### SelectNamedObjectTypes(IReadOnlyCollection&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Selects entity and relationship types in the TOC.</p>


```csharp
public void SelectNamedObjectTypes(IReadOnlyCollection<string> namedObjectTypes)
```
### SelectRelationships(IReadOnlyCollection&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Selects relationship types in the TOC.</p>


```csharp
public void SelectRelationships(IReadOnlyCollection<string> relationships)
```
### SetSearchOptions(SearchOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Sets the search options for the Knowledge Graph investigation view.</p>


```csharp
public void SetSearchOptions(SearchOptions searchOptions)
```
### SetSelectedRecords(KnowledgeGraphLayerIDSet, SelectionCombinationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Sets the selected records. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphLayerIDSet SetSelectedRecords(KnowledgeGraphLayerIDSet idSet, SelectionCombinationMethod method)
```
### SubmitQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Performs an openCypher query on the knowledge graph.
The investigation view is placed in Query Mode.</p>


```csharp
public void SubmitQuery(string queryText)
```
### SubmitSearch(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.yml" sourcestartlinenumber="1">Performs a text search on the knowledge graph.
The investigation view is placed in Search Mode and uses the current search scope and filters.
To customize the search scope and filters use <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.SetSearchOptions(ArcGIS.Desktop.KnowledgeGraph.SearchOptions)" data-throw-if-not-resolved="false"></xref> prior to submitting the search.</p>


```csharp
public void SubmitSearch(string searchText)
```


