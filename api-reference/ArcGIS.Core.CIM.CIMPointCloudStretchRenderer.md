# CIMPointCloudStretchRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Represents a point cloud stretch renderer.</p>


## Object Signature

```csharp
public class CIMPointCloudStretchRenderer : CIMPointCloudRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointCloudStretchRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Represents a point cloud stretch renderer.</p>


```csharp
public CIMPointCloudStretchRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointCloudStretchRenderer.</p>


```csharp
public CIMPointCloudStretchRenderer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp of the renderer.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMPointCloudStretchRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointCloudStretchRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### RangeMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum value used to compute the linear mapping of the renderer.</p>


```csharp
public double RangeMax { get; set; }
```
### RangeMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the minimum value used to compute the linear mapping of the renderer.</p>


```csharp
public double RangeMin { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointCloudStretchRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudStretchRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


