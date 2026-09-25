# CIMGeotriggerDeviceLocationFeed

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerDeviceLocationFeed.yml" sourcestartlinenumber="1">Represents a Geotrigger feed that uses the device location to provide updates.</p>


## Object Signature

```csharp
public class CIMGeotriggerDeviceLocationFeed : CIMGeotriggerFeed, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeotriggerDeviceLocationFeed()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerDeviceLocationFeed.yml" sourcestartlinenumber="1">Represents a Geotrigger feed that uses the device location to provide updates.</p>


```csharp
public CIMGeotriggerDeviceLocationFeed()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerDeviceLocationFeed.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeotriggerDeviceLocationFeed.</p>


```csharp
public CIMGeotriggerDeviceLocationFeed Clone()
```
### FilterExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerDeviceLocationFeed.yml" sourcestartlinenumber="1">Gets or sets the arcade expression that controls whether a location update will be used by a geotrigger. This expression uses the Location Update Constraint Arcade profile. The expression should return a Boolean where false indicates the location will not be used.</p>


```csharp
public CIMExpressionInfo FilterExpression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerDeviceLocationFeed.yml" sourcestartlinenumber="1">Reconstructs the CIMGeotriggerDeviceLocationFeed with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeotriggerDeviceLocationFeed FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerDeviceLocationFeed.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerDeviceLocationFeed.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeotriggerDeviceLocationFeed and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerDeviceLocationFeed.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


