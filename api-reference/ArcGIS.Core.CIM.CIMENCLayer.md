# CIMENCLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Represents an Electronic Navigational Charts (ENC) layer.</p>


## Object Signature

```csharp
public class CIMENCLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p>
    ENC layers allow to visualize nautical charts from S-57 cells using S-52 symbology.
    </p>


## Members

### CIMENCLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Represents an Electronic Navigational Charts (ENC) layer.</p>


```csharp
public CIMENCLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMENCLayer.</p>


```csharp
public CIMENCLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection to the ENC resource.</p>


```csharp
public CIMENCDataConnection DataConnection { get; set; }
```
### DisplaySettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Gets or sets the display settings of the ENC layer.</p>


```csharp
public CIMENCDisplaySettings DisplaySettings { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMENCLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMENCLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is selectable.</p>


```csharp
public bool Selectable { get; set; }
```
### SelectionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the selection set for the layer.</p>


```csharp
public string SelectionSetURI { get; set; }
```
### SubLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Gets or sets a collection of ENCSubLayers, used to access features by type.</p>


```csharp
public CIMENCSubLayer[] SubLayers { get; set; }
```
### SubTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Gets or sets a collection of ENCSubTables.</p>


```csharp
public CIMENCSubTable[] SubTables { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMENCLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


