# CIMAutoCamera

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Represents the camera settings associated with a map frame on a page layout.</p>


## Object Signature

```csharp
public class CIMAutoCamera : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAutoCamera()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Represents the camera settings associated with a map frame on a page layout.</p>


```csharp
public CIMAutoCamera()
```
### AutoCameraType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the camera type.</p>


```csharp
public AutoCameraType AutoCameraType { get; set; }
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the camera associated with the map frame.</p>


```csharp
public CIMViewCamera Camera { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAutoCamera.</p>


```csharp
public CIMAutoCamera Clone()
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the extent for a map frame when using the fixed constraint.</p>


```csharp
public Envelope Extent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Reconstructs the CIMAutoCamera with a specified state from a JSON encoding.</p>


```csharp
public static CIMAutoCamera FromJson(string json, JsonDeserializationSettings settings = null)
```
### IntersectLayerPath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the layer being used to set the camera when using the map frame link constraint.</p>


```csharp
public string IntersectLayerPath { get; set; }
```
### MapFrameLinkName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the map frame name being used to set the camera when using the map frame link constraint.</p>


```csharp
public string MapFrameLinkName { get; set; }
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the margin value for a map frame with a map frame link constraint.</p>


```csharp
public double Margin { get; set; }
```
### MarginType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the margin type for a map frame with a map frame link constraint.</p>


```csharp
public UnitType MarginType { get; set; }
```
### MarginUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the margin units for a map frame with a map frame link constraint.</p>


```csharp
public Unit MarginUnits { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Source

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets the extent constraint associated with the map frame.</p>


```csharp
public AutoCameraSource Source { get; set; }
```
### SyncRotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the map frame should rotate when using a map frame link constraint.</p>


```csharp
public bool SyncRotation { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAutoCamera and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAutoCamera.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


