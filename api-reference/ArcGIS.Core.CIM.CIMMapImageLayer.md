# CIMMapImageLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapImageLayer.yml" sourcestartlinenumber="1">Represents an ArcGIS Map Service layer.</p>


## Object Signature

```csharp
public class CIMMapImageLayer : CIMDynamicServiceLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapImageLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapImageLayer.yml" sourcestartlinenumber="1">Represents an ArcGIS Map Service layer.</p>


```csharp
public CIMMapImageLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapImageLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapImageLayer.</p>


```csharp
public CIMMapImageLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapImageLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMMapImageLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapImageLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapImageLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapImageLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapImageLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapImageLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


