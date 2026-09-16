# CIMFenceGeotrigger

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Represents a fence geotrigger.</p>


## Object Signature

```csharp
public class CIMFenceGeotrigger : CIMGeotrigger, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFenceGeotrigger()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Represents a fence geotrigger.</p>


```csharp
public CIMFenceGeotrigger()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFenceGeotrigger.</p>


```csharp
public CIMFenceGeotrigger Clone()
```
### EnterExitRule

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Gets or sets exit rule for the fence.</p>


```csharp
public GeoFenceEnterExitRule EnterExitRule { get; set; }
```
### Feed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Gets or sets Feed.</p>


```csharp
public CIMGeotriggerFeed Feed { get; set; }
```
### FeedAccuracyMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Gets or sets accuracy mode for the fence.</p>


```csharp
public GeotriggerAccuracyMode FeedAccuracyMode { get; set; }
```
### FenceNotificationRule

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Gets or sets notification rule for this fence.</p>


```csharp
public GeoFenceNotificationRule FenceNotificationRule { get; set; }
```
### FenceParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Gets or sets exit rule for the fence.</p>


```csharp
public CIMGeotriggerFenceParameters FenceParameters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Reconstructs the CIMFenceGeotrigger with a specified state from a JSON encoding.</p>


```csharp
public static CIMFenceGeotrigger FromJson(string json, JsonDeserializationSettings settings = null)
```
### NotificationOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Gets or sets notification properties.</p>


```csharp
public CIMGeotriggerNotificationProperties NotificationOptions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFenceGeotrigger and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFenceGeotrigger.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


