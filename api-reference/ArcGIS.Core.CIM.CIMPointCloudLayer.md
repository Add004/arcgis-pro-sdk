# CIMPointCloudLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Represents a point cloud layer.</p>


## Object Signature

```csharp
public class CIMPointCloudLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointCloudLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Represents a point cloud layer.</p>


```csharp
public CIMPointCloudLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointCloudLayer.</p>


```csharp
public CIMPointCloudLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMSceneDataConnection DataConnection { get; set; }
```
### EyeDomeLighting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Gets or sets eye-dome lighting properties.</p>


```csharp
public CIMEyeDomeLighting EyeDomeLighting { get; set; }
```
### Filters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Gets or sets the filter used to filter the points being drawn.</p>


```csharp
public CIMPointCloudFilter[] Filters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMPointCloudLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointCloudLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### PointsBudget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Gets or sets the double value to determine the upper limit on the number of points drawn.</p>


```csharp
public int PointsBudget { get; set; }
```
### PointsPerInch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Gets or sets the double value that determines the number of points to draw per display inch.</p>


```csharp
public double PointsPerInch { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Gets or sets the symbol renderer.</p>


```csharp
public CIMPointCloudRenderer Renderer { get; set; }
```
### Snappable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer participates in snapping in the editor.</p>


```csharp
public bool Snappable { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointCloudLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


