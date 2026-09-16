# CIMGISProject

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Represents a project.</p>


## Object Signature

```csharp
public class CIMGISProject : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGISProject()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Represents a project.</p>


```csharp
public CIMGISProject()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGISProject.</p>


```csharp
public CIMGISProject Clone()
```
### DatabaseConnections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the database connections of the project.</p>


```csharp
public CIMWorkspaceConnection[] DatabaseConnections { get; set; }
```
### DefaultFolder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the default folder of the project.</p>


```csharp
public string DefaultFolder { get; set; }
```
### DefaultGeoDatabase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the path of the default geodatabase of the project.</p>


```csharp
public string DefaultGeoDatabase { get; set; }
```
### DefaultSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets a WKT string representation of the default spatial reference of the project.</p>


```csharp
public string DefaultSpatialReference { get; set; }
```
### DefaultToolbox

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the path of the default toolbox of the project.</p>


```csharp
public string DefaultToolbox { get; set; }
```
### DisplayUnitSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the display unit settings for the project.</p>


```csharp
public CIMDisplayUnitSettings DisplayUnitSettings { get; set; }
```
### FolderConnections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the folder connections of the project.</p>


```csharp
public CIMFolderConnection[] FolderConnections { get; set; }
```
### ForceUpdate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to force update an updatable project.</p>


```csharp
public bool ForceUpdate { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Reconstructs the CIMGISProject with a specified state from a JSON encoding.</p>


```csharp
public static CIMGISProject FromJson(string json, JsonDeserializationSettings settings = null)
```
### MemoryWorkspaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the memory workspaces of the project.</p>


```csharp
public CIMMemoryWorkspace[] MemoryWorkspaces { get; set; }
```
### ModuleSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the module settings of the project.</p>


```csharp
public CIMModuleSettings[] ModuleSettings { get; set; }
```
### ProjectItems

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the items of the project.</p>


```csharp
public CIMProjectItem[] ProjectItems { get; set; }
```
### ProjectMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the path to an XML file in the same folder as the APRX that contains metadata about the project.</p>


```csharp
public string ProjectMetadata { get; set; }
```
### ReadOnly

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the project is read only for updatable projects.</p>


```csharp
public bool ReadOnly { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServerConnections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the service connections of the project.</p>


```csharp
public CIMServerConnection[] ServerConnections { get; set; }
```
### SourceModifiedTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the time the project was last modified.</p>


```csharp
public TimeInstant SourceModifiedTime { get; set; }
```
### SourceURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the source URI of the project. Set if sourced from an external item such as an item on a portal.</p>


```csharp
public string SourceURI { get; set; }
```
### ThumbnailOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the thumbnail generation options for the project.</p>


```csharp
public CIMProjectThumbnailOptions ThumbnailOptions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGISProject and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ViewLayoutXML

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets an XML representation of the view layout used for the project.</p>


```csharp
public string ViewLayoutXML { get; set; }
```
### Views

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Gets or sets the views of the project.</p>


```csharp
public CIMView[] Views { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGISProject.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


