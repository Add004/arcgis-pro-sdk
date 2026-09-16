# CIMNitfGroupSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Represents NITF group sub layer.</p>


## Object Signature

```csharp
public class CIMNitfGroupSubLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNitfGroupSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Represents NITF group sub layer.</p>


```csharp
public CIMNitfGroupSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNitfGroupSubLayer.</p>


```csharp
public CIMNitfGroupSubLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMNitfGroupSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNitfGroupSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Gets or sets the layer URIs of the child layers.</p>


```csharp
public string[] Layers { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNitfGroupSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfGroupSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


