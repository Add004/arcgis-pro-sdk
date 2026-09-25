# LayerDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Represents the content of a .lyrx file; that is the visualization properties, symbology and date references of one or more
MapMembers.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="6">The LayerDocument can be built from a .lyrx file, one or more <xref href="ArcGIS.Desktop.Mapping.MapMember?text=MapMembers" data-throw-if-not-resolved="false"></xref> or a
<xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LayerDocument : Document
```


## Members

### LayerDocument(CIMLayerDocument)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Creates a LayerDocument instance using a <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LayerDocument(CIMLayerDocument layerDoc = null)
```
### LayerDocument(MapMember)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Creates a LayerDocument instance from a MapMember object.
This constructor must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LayerDocument(MapMember mapMember)
```
### LayerDocument(IEnumerable&lt;MapMember&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Creates a LayerDocument instance from a set of MapMember objects.
This constructor must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LayerDocument(IEnumerable<MapMember> mapMembers)
```
### LayerDocument(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Creates a LayerDocument instance from a Layer File (.lyrx).
This constructor must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LayerDocument(string layerXFilePath)
```
### AsJson()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Create a json encoding for the <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref> and its current state.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string AsJson()
```
### GetCIMLayerDocument()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref> instance.</p>


```csharp
public CIMLayerDocument GetCIMLayerDocument()
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Gets if the LayerDocument is valid; that is if a <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref> exists.</p>


```csharp
public bool IsValid { get; }
```
### Load(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Populates a LayerDocument from a json string that represents <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Load(string json)
```
### LoadFromPath(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Loads from Layer File (.lyrx)
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void LoadFromPath(string layerXFile)
```
### Save(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerDocument.yml" sourcestartlinenumber="1">Save as a Layer File (.lyrx)
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Save(string layerXFilePath)
```


