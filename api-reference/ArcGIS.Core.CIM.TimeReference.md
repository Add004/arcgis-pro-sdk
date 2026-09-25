# TimeReference

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Represents the time zone definition for a given date and time.</p>


## Object Signature

```csharp
public class TimeReference : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### TimeReference()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Represents the time zone definition for a given date and time.</p>


```csharp
public TimeReference()
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Reconstructs the TimeReference with a specified state from a JSON encoding.</p>


```csharp
public static TimeReference FromJson(string json)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RespectsDaylightSavingTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the time reference should honor daylight savings time.</p>


```csharp
public bool RespectsDaylightSavingTime { get; set; }
```
### RespectsDynamicAdjustmentRules

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the time reference should respect dynamic rules for adjusting with daylight savings time for specific years.</p>


```csharp
public bool RespectsDynamicAdjustmentRules { get; set; }
```
### TimeZoneIanaID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Gets or sets the iana id for the time zone.</p>


```csharp
public string TimeZoneIanaID { get; set; }
```
### TimeZoneNameID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Gets or sets the windows id for the time zone.</p>


```csharp
public string TimeZoneNameID { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Creates a JSON encoding of the TimeReference and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeReference.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


