# CIMCustomGrid

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Represents a custom grid of the mapFrame.</p>


## Object Signature

```csharp
public class CIMCustomGrid : CIMMapGrid, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCustomGrid()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Represents a custom grid of the mapFrame.</p>


```csharp
public CIMCustomGrid()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCustomGrid.</p>


```csharp
public CIMCustomGrid Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Reconstructs the CIMCustomGrid with a specified state from a JSON encoding.</p>


```csharp
public static CIMCustomGrid FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Gets or sets the gridLines of the custom grid. These are limited to ticks, labels, and tabs.</p>


```csharp
public CIMGridLine[] GridLines { get; set; }
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Gets or sets the path to the layer used to define the grid lines.</p>


```csharp
public string LayerURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCustomGrid and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseMapClipShape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the clip shape of the map (if set) as the grid boundary.</p>


```csharp
public bool UseMapClipShape { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGrid.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


