# CIMGraphicElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicElement.yml" sourcestartlinenumber="1">Represents the CIM representation of an element on a page layout.</p>


## Object Signature

```csharp
public class CIMGraphicElement : CIMElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGraphicElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicElement.yml" sourcestartlinenumber="1">Represents the CIM representation of an element on a page layout.</p>


```csharp
public CIMGraphicElement()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGraphicElement.</p>


```csharp
public CIMGraphicElement Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicElement.yml" sourcestartlinenumber="1">Reconstructs the CIMGraphicElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMGraphicElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### Graphic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicElement.yml" sourcestartlinenumber="1">Gets or sets the CIMGraphic for an element on a page layout.</p>


```csharp
public CIMGraphic Graphic { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGraphicElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


