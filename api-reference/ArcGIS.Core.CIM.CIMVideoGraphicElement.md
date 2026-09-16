# CIMVideoGraphicElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoGraphicElement.yml" sourcestartlinenumber="1">Represents video-related graphic being displayed on the map.</p>


## Object Signature

```csharp
public class CIMVideoGraphicElement : CIMGraphicElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVideoGraphicElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoGraphicElement.yml" sourcestartlinenumber="1">Represents video-related graphic being displayed on the map.</p>


```csharp
public CIMVideoGraphicElement()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoGraphicElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVideoGraphicElement.</p>


```csharp
public CIMVideoGraphicElement Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoGraphicElement.yml" sourcestartlinenumber="1">Reconstructs the CIMVideoGraphicElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMVideoGraphicElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoGraphicElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoGraphicElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVideoGraphicElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoGraphicElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


