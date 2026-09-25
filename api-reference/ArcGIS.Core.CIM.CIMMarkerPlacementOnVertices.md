# CIMMarkerPlacementOnVertices

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Represents a marker placement on vertices which places a single marker on a line or polygon outline at a set distance from the middle or one of the endpoints.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementOnVertices : CIMMarkerStrokePlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementOnVertices()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Represents a marker placement on vertices which places a single marker on a line or polygon outline at a set distance from the middle or one of the endpoints.</p>


```csharp
public CIMMarkerPlacementOnVertices()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementOnVertices.</p>


```csharp
public CIMMarkerPlacementOnVertices Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementOnVertices with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementOnVertices FromJson(string json, JsonDeserializationSettings settings = null)
```
### PlaceOnControlPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a marker will be placed on the control points of the line.</p>


```csharp
public bool PlaceOnControlPoints { get; set; }
```
### PlaceOnEndPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a marker will be placed on the endpoints of the line.</p>


```csharp
public bool PlaceOnEndPoints { get; set; }
```
### PlaceOnRegularVertices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a marker will be placed on the vertices of the line.</p>


```csharp
public bool PlaceOnRegularVertices { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementOnVertices and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnVertices.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


