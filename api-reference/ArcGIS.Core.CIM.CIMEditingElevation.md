# CIMEditingElevation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Defines the properties needed to specify new Z values when creating or modifying features.</p>


## Object Signature

```csharp
public class CIMEditingElevation : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMEditingElevation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Defines the properties needed to specify new Z values when creating or modifying features.</p>


```csharp
public CIMEditingElevation()
```
### CaptureMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Gets or sets the elevation capture mode.</p>


```csharp
public EditingElevationCaptureMode CaptureMode { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Creates a deep copy of CIMEditingElevation.</p>


```csharp
public CIMEditingElevation Clone()
```
### ConstantValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Gets or sets the value used when CaptureMode is Constant.</p>


```csharp
public double ConstantValue { get; set; }
```
### ConstantValueUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Gets or sets the Unit used when CaptureMode is Constant.</p>


```csharp
public LinearUnit ConstantValueUnit { get; set; }
```
### ElevationSurfaceLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Gets or sets the URI of the elevation surface layer to be used when CaptureMode is Surface.</p>


```csharp
public string ElevationSurfaceLayerURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Reconstructs the CIMEditingElevation with a specified state from a JSON encoding.</p>


```csharp
public static CIMEditingElevation FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMEditingElevation and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingElevation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


