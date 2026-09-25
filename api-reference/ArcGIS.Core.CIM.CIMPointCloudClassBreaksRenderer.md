# CIMPointCloudClassBreaksRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudClassBreaksRenderer.yml" sourcestartlinenumber="1">Represents a point cloud class breaks renderer.</p>


## Object Signature

```csharp
public class CIMPointCloudClassBreaksRenderer : CIMPointCloudRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointCloudClassBreaksRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudClassBreaksRenderer.yml" sourcestartlinenumber="1">Represents a point cloud class breaks renderer.</p>


```csharp
public CIMPointCloudClassBreaksRenderer()
```
### Breaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the color class breaks of the renderer.</p>


```csharp
public CIMColorClassBreak[] Breaks { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudClassBreaksRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointCloudClassBreaksRenderer.</p>


```csharp
public CIMPointCloudClassBreaksRenderer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudClassBreaksRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMPointCloudClassBreaksRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointCloudClassBreaksRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudClassBreaksRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudClassBreaksRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointCloudClassBreaksRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudClassBreaksRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


