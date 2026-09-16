# EditingTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Templates.html">Templates</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Defines how a new feature is created for a particular <xref href="ArcGIS.Desktop.Mapping.MapMember?text=MapMember" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class EditingTemplate : PropertyChangedBase
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">You create new features using feature templates that contain configurable toolsets, attributes,
and other properties that define how a new feature is created.</p>


## Members

### ActivateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Activates this EditingTemplate, without changing the current tool.</p>


```csharp
public Task ActivateAsync()
```
### ActivateDefaultToolAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Activates the Tool that is identified by <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate.DefaultToolID" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Task ActivateDefaultToolAsync()
```
### ActivateLastSelectedToolAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Activates the Tool that is identified by <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate.LastSelectedToolID" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Task ActivateLastSelectedToolAsync()
```
### ActivateToolAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Activates a Tool that is identified by the given ID.</p>


```csharp
public Task ActivateToolAsync(string damlID)
```
### CanBeGroupTemplatePart

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets whether this EditingTemplate can be included as part of a GroupTemplate.</p>


```csharp
public bool CanBeGroupTemplatePart { get; }
```
### Current

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the currently active <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static EditingTemplate Current { get; }
```
### DefaultToolID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the DAML ID of the Tool that is currently chosen as this EditingTemplate's DefaultTool.</p>


```csharp
public string DefaultToolID { get; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the description of this EditingTemplate.</p>


```csharp
public string Description { get; }
```
### GeneratePreviewAsync(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Generates a preview icon that represents this EditingTemplate.</p>


```csharp
public Task<ImageSource> GeneratePreviewAsync(int width, int height)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the CIM definition of this EditingTemplate. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMEditingTemplate GetDefinition()
```
### GetSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Retrieves the symbol that would be used by a feature created from this template. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMSymbolReference GetSymbol()
```
### GetSymbolAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the symbol that would be used by a feature created from this template.</p>


```csharp
public Task<CIMSymbolReference> GetSymbolAsync()
```
### GetToolOptions(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the ToolOptions for specified Tool.</p>


```csharp
public ReadOnlyToolOptions GetToolOptions(string toolID)
```
### HasActiveTool

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets whether the application's current tool is the last selected Tool for this EditingTemplate.</p>


```csharp
public bool HasActiveTool { get; }
```
### Inspector

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the Inspector that contains the Attributes associated with this EditingTemplate.</p>


```csharp
public abstract Inspector Inspector { get; }
```
### IsActive

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets whether this EditingTemplate is currently being used and its last selected Tool is currently the active Tool.</p>


```csharp
public bool IsActive { get; }
```
### IsCurrent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets whether this EditingTemplate is the template currently being used.</p>


```csharp
public bool IsCurrent { get; }
```
### LastSelectedToolID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the DAML ID of the Tool that was most recently selected when using this EditingTemplate.</p>


```csharp
public string LastSelectedToolID { get; }
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the Layer that is associated with this EditingTemplate.</p>


```csharp
public Layer Layer { get; }
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the Map that contains the associated <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate.MapMember" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public virtual Map Map { get; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the MapMember that is associated with this EditingTemplate.</p>


```csharp
public MapMember MapMember { get; protected set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the name of this EditingTemplate.</p>


```csharp
public string Name { get; }
```
### PassesDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets whether this EditingTemplate's Attributes pass the MapMember's DefinitionQuery.</p>


```csharp
public abstract bool PassesDefinitionQuery { get; }
```
### RegisteredToolIDs

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the the tool daml ids that are registered to the template (template type, template geometry type etc). ie the set that displays in Template Properties.</p>


```csharp
public IReadOnlyCollection<string> RegisteredToolIDs { get; }
```
### SetDefinition(CIMEditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Sets the CIM definition of this EditingTemplate. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMEditingTemplate definition)
```
### ShowProperties(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Shows the properties of this EditingTemplate in a property sheet.</p>


```csharp
public Task ShowProperties(string pageID = null)
```
### StandaloneTable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the StandaloneTable that is associated with this EditingTemplate.</p>


```csharp
public StandaloneTable StandaloneTable { get; }
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets the collection of Tags that help to make this EditingTemplate searchable.</p>


```csharp
public IReadOnlyCollection<string> Tags { get; }
```
### ToolIDs

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingTemplate.yml" sourcestartlinenumber="1">Gets a collection of DAML IDs for each of the Tools that are available for use with this EditingTemplate.</p>


```csharp
public IReadOnlyCollection<string> ToolIDs { get; }
```


