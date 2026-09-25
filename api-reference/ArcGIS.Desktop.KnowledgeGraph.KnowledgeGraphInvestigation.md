# KnowledgeGraphInvestigation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Represents a Knowledge Graph investigation in a project and provides access to the entities, relationships and other items in the
knowledge graph.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphInvestigation
```

## Remarks

<p>To create a KnowledgeGraphInvestigation, you must call a create method of the
    <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationFactory?text=KnowledgeGraphInvestigationFactory" data-throw-if-not-resolved="false"></xref> class.
    </p>
<p>
    To open a KnowledgeGraphInvestigation, use the
    <xref href="ArcGIS.Desktop.Core.ProApp.Panes.CreateInvestigationPane?text=ProApp.Panes.CreateInvestigationPane" data-throw-if-not-resolved="false"></xref> method.
    </p>
<p>
    You need to use a <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView?text=KnowledgeGraphInvestigationView" data-throw-if-not-resolved="false"></xref> to interact with a KnowledgeGraphInvestigation.
    Multiple KnowledgeGraphInvestigationViews can be opened for a KnowledgeGraphInvestigation at a given time, but there can only be one active
    KnowledgeGraphInvestigationView which is returned by the <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.Active?text=KnowledgeGraphInvestigation.Active" data-throw-if-not-resolved="false"></xref>
    static member.  Use the <xref href="KnowledgeGraphInvestigationView.Active.KnowledgeGraphInvestigation?text=KnowledgeGraphInvestigation" data-throw-if-not-resolved="false"></xref>
    property to access the KnowledgeGraphInvestigation object associated with the KnowledgeGraphInvestigationView.
    </p>


## Members

### AddFilteredFindPathsConfiguration(CIMFilteredFindPathsConfiguration)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Adds a <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration" data-throw-if-not-resolved="false"></xref> to this investigation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddFilteredFindPathsConfiguration(CIMFilteredFindPathsConfiguration filteredFindPathsConfiguration)
```
### AddQueryDefinition(CIMKnowledgeGraphQueryDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Adds a <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition" data-throw-if-not-resolved="false"></xref> to this investigation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddQueryDefinition(CIMKnowledgeGraphQueryDefinition queryDefinition)
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMWorkspaceConnection" data-throw-if-not-resolved="false"></xref> of the investigation.</p>


```csharp
public CIMWorkspaceConnection DataConnection { get; }
```
### DeleteFilteredFindPathsConfiguration(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Deletes the <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration" data-throw-if-not-resolved="false"></xref> with the specified name from this investigation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteFilteredFindPathsConfiguration(string filteredFindPathsConfigurationName)
```
### DeleteQueryDefinition(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Deletes the <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition" data-throw-if-not-resolved="false"></xref> with the specified name from this investigation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteQueryDefinition(string queryDefinitionName)
```
### ExportFilteredFindPathsConfiguration(CIMFilteredFindPathsConfiguration, string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Exports the specified <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration" data-throw-if-not-resolved="false"></xref> to the file path.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ExportFilteredFindPathsConfiguration(CIMFilteredFindPathsConfiguration filteredFindPathsConfiguration, string filePath, bool overwrite)
```
### GetAllFilteredFindPathsConfigurations()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets all the <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration" data-throw-if-not-resolved="false"></xref>s for this investigation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<CIMFilteredFindPathsConfiguration> GetAllFilteredFindPathsConfigurations()
```
### GetAllQueryDefinitions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets all the <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition" data-throw-if-not-resolved="false"></xref>s for this investigation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<CIMKnowledgeGraphQueryDefinition> GetAllQueryDefinitions()
```
### GetFilteredFindPathsConfiguration(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration" data-throw-if-not-resolved="false"></xref> with the specified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMFilteredFindPathsConfiguration GetFilteredFindPathsConfiguration(string filteredFindPathsConfigurationName)
```
### GetInvestigationPanes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Get the collection of investigation panes for the investigation.</p>


```csharp
public IReadOnlyList<IKnowledgeGraphInvestigationPane> GetInvestigationPanes()
```
### GetQueryDefinition(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition" data-throw-if-not-resolved="false"></xref> with the specified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMKnowledgeGraphQueryDefinition GetQueryDefinition(string queryDefinitionName)
```
### GraphName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets the graph name of the investigation.</p>


```csharp
public string GraphName { get; }
```
### ImportFilteredFindPathsConfiguration(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Import a filtered find paths configuration from a filtered find paths configuration file (*.ffpcfg) and add it to the investigation.</p>


```csharp
public Task<CIMFilteredFindPathsConfiguration> ImportFilteredFindPathsConfiguration(string filePath)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets the name of the investigation.</p>


```csharp
public string Name { get; }
```
### OpenViewAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Open a new view for this investigation.</p>


```csharp
public Task OpenViewAsync()
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets the OperationManager.</p>


```csharp
public OperationManager OperationManager { get; }
```
### RenameFilteredFindPathsConfiguration(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Renames the <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration" data-throw-if-not-resolved="false"></xref> with the specified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RenameFilteredFindPathsConfiguration(string filteredFindPathsConfigurationName, string newFilteredFindPathsConfigurationName)
```
### RenameQueryDefinition(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Renames the <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition" data-throw-if-not-resolved="false"></xref> with the specified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RenameQueryDefinition(string queryDefinitionName, string newQueryDefinitionName)
```
### ServiceUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets the service uri of the investigation.</p>


```csharp
public string ServiceUri { get; }
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Sets the investigation name.   It is important that all investigations have a unique name so they can be easily referenced.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetName(string newName)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets the investigation CIM path.</p>


```csharp
public string URI { get; }
```
### UpdateFilteredFindPathsConfiguration(CIMFilteredFindPathsConfiguration)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Updates the specified <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateFilteredFindPathsConfiguration(CIMFilteredFindPathsConfiguration filteredFindPathsConfiguration)
```
### UpdateQueryDefinition(CIMKnowledgeGraphQueryDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Updates the specified <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateQueryDefinition(CIMKnowledgeGraphQueryDefinition queryDefinition)
```
### UpdateQueryDefinition(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Updates the specified <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition" data-throw-if-not-resolved="false"></xref> with the new openCypher text.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateQueryDefinition(string queryDefinitionName, string newOpenCypherText)
```


