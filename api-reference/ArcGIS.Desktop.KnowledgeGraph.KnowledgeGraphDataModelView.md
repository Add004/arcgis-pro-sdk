# KnowledgeGraphDataModelView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Represents the data model view of a Knowledge Graph investigation in a pane.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphDataModelView
```

## Remarks

<p>
    A project can contain multiple investigations.  An data model view is simply a view of an investigation. 
    The KnowledgeGraphDataModelView class provides methods and properties to navigate and interact with items in the investigation. 
    </p>
<p>
    There can be multiple data model views open at a given time, but there can only be one active data model view.
    The active data model view will set the context for the ribbon and many of the dock panes in the application.
    For example, the Contents pane will reflect the items of the active data model view's investigation.
    The instance of the active data model view can be accessed via the static the <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.Active" data-throw-if-not-resolved="false"></xref> property. 
    The property will return null if there is no active data model view.
    </p>
<p>
    The data model view also provides the context for managing selected items in the Contents pane.  
    For example, the <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.GetSelectedEntities" data-throw-if-not-resolved="false"></xref> method returns a collection of entities that
    are currently selected in the Contents pane.
    </p>


## Members

### Active

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets the active Knowledge Graph data model view.</p>


```csharp
public static KnowledgeGraphDataModelView Active { get; }
```
### ClearTOCSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Clears the selection from the TOC.</p>


```csharp
public void ClearTOCSelection()
```
### ColorCodeEntities

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets and sets whether to color code entities.</p>


```csharp
public bool ColorCodeEntities { get; set; }
```
### ColorCodeRelationships

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets and sets whether to color code relationships.</p>


```csharp
public bool ColorCodeRelationships { get; set; }
```
### FitToContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Set the extent to fit the content.</p>


```csharp
public void FitToContent()
```
### GetKnowledgeGraph()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets the Knowledge Graph associated with the data model view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraph GetKnowledgeGraph()
```
### GetSelectedEntities()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets the collection of entities selected in the TOC.</p>


```csharp
public IReadOnlyList<string> GetSelectedEntities()
```
### GetSelectedRelationships()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets the collection of relationships selected in the TOC.</p>


```csharp
public IReadOnlyList<string> GetSelectedRelationships()
```
### IsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets a value that indicates whether the KnowledgeGraphInvestigationView can be accessed.
This property is <code>false</code> while the investigation view processes major operations like initializing.</p>


```csharp
public bool IsReady { get; }
```
### Mode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets the mode.</p>


```csharp
public KnowledgeGraphDataModelMode Mode { get; }
```
### RefreshAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Refreshes the view.  This must be called on the GUI thread.</p>


```csharp
public Task RefreshAsync()
```
### SelectAll()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Selects all entities and relationships in the TOC.</p>


```csharp
public void SelectAll()
```
### SelectEntities(IReadOnlyCollection&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Selects entities in the TOC.</p>


```csharp
public void SelectEntities(IReadOnlyCollection<string> entities)
```
### SelectNamedObjectTypes(IReadOnlyCollection&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Selects entities and relationships in the TOC.</p>


```csharp
public void SelectNamedObjectTypes(IReadOnlyCollection<string> namedObjectTypes)
```
### SelectRelationships(IReadOnlyCollection&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Selects relationships in the TOC.</p>


```csharp
public void SelectRelationships(IReadOnlyCollection<string> relationships)
```
### ServiceUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets the Knowledge Graph service uri associated with the data model view.</p>


```csharp
public string ServiceUri { get; }
```
### SetMode(KnowledgeGraphDataModelMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Sets the mode.</p>


```csharp
public void SetMode(KnowledgeGraphDataModelMode mode)
```
### SetNodeAlignment(NodeAlignment)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Sets the node alignment.</p>


```csharp
public void SetNodeAlignment(NodeAlignment alignment)
```
### SetZoomLevel(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Set the zoom level for the data model view. The allowed values are 1 to 200.</p>


```csharp
public void SetZoomLevel(int zoomLevel)
```
### ShowDetails

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets and sets whether to show the details pane.</p>


```csharp
public bool ShowDetails { get; set; }
```
### ZoomInFixed()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Zooms in by a fixed amount.</p>


```csharp
public void ZoomInFixed()
```
### ZoomLevel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Gets the zoom level for the data model view.</p>


```csharp
public int ZoomLevel { get; }
```
### ZoomOutFixed()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Zoom out by a fixed amount</p>


```csharp
public void ZoomOutFixed()
```
### ZoomToSelected()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphDataModelView.yml" sourcestartlinenumber="1">Zoom to the extent of the selected items in the view.</p>


```csharp
public void ZoomToSelected()
```


