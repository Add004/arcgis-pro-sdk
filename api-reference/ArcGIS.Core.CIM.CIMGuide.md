# CIMGuide

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Represents a guide used to snap elements on a page layout.</p>


## Object Signature

```csharp
public class CIMGuide : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGuide()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Represents a guide used to snap elements on a page layout.</p>


```csharp
public CIMGuide()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGuide.</p>


```csharp
public CIMGuide Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Reconstructs the CIMGuide with a specified state from a JSON encoding.</p>


```csharp
public static CIMGuide FromJson(string json, JsonDeserializationSettings settings = null)
```
### Orientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Gets or sets the horizontal or vertical orientation of the guide.</p>


```csharp
public Orientation Orientation { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Gets or sets the position of the guide.</p>


```csharp
public double Position { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGuide and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGuide.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


