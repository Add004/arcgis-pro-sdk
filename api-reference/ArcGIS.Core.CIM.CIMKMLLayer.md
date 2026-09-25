# CIMKMLLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Represents a KML layer.</p>


## Object Signature

```csharp
public class CIMKMLLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKMLLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Represents a KML layer.</p>


```csharp
public CIMKMLLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKMLLayer.</p>


```csharp
public CIMKMLLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection to the KML resource.</p>


```csharp
public CIMKMLDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMKMLLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMKMLLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### LabelVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display labels for this KML layer's placemarks.</p>


```csharp
public bool LabelVisibility { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is selectable.</p>


```csharp
public bool Selectable { get; set; }
```
### SelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Gets or sets the selection color.</p>


```csharp
public CIMColor SelectionColor { get; set; }
```
### TextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Gets or sets the text symbol used to label placemarks.</p>


```csharp
public CIMTextSymbol TextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKMLLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the selection color.</p>


```csharp
public bool UseSelectionColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKMLLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


