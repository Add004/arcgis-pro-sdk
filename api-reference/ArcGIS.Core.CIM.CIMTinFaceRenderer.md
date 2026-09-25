# CIMTinFaceRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinFaceRenderer.yml" sourcestartlinenumber="1">Represents a TIN face renderer.</p>


## Object Signature

```csharp
public class CIMTinFaceRenderer : CIMTinSimpleRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTinFaceRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinFaceRenderer.yml" sourcestartlinenumber="1">Represents a TIN face renderer.</p>


```csharp
public CIMTinFaceRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinFaceRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTinFaceRenderer.</p>


```csharp
public CIMTinFaceRenderer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinFaceRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMTinFaceRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTinFaceRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinFaceRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinFaceRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTinFaceRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinFaceRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


