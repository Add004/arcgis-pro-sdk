# CIMWMSSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Represents a WMS service sublayer.</p>


## Object Signature

```csharp
public class CIMWMSSubLayer : CIMSubLayerBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMWMSSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Represents a WMS service sublayer.</p>


```csharp
public CIMWMSSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMWMSSubLayer.</p>


```csharp
public CIMWMSSubLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMWMSSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMWMSSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowPopups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show pop-ups.</p>


```csharp
public bool ShowPopups { get; set; }
```
### StyleName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Gets or sets the style name.</p>


```csharp
public string StyleName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMWMSSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


