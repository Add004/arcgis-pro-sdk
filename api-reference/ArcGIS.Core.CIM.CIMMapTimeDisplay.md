# CIMMapTimeDisplay

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Represents map time display.</p>


## Object Signature

```csharp
public class CIMMapTimeDisplay : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapTimeDisplay()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Represents map time display.</p>


```csharp
public CIMMapTimeDisplay()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapTimeDisplay.</p>


```csharp
public CIMMapTimeDisplay Clone()
```
### CurrentTimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets the current time extent.</p>


```csharp
public TimeExtent CurrentTimeExtent { get; set; }
```
### DefaultTimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets the default time interval.</p>


```csharp
public double DefaultTimeInterval { get; set; }
```
### DefaultTimeIntervalUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets the default time interval units.</p>


```csharp
public esriTimeUnits DefaultTimeIntervalUnits { get; set; }
```
### DefaultTimeWindow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets the default time window.</p>


```csharp
public double DefaultTimeWindow { get; set; }
```
### DisplayDatesInMapTimeZone

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether date field values should be projected to the map's time reference for display.</p>


```csharp
public bool DisplayDatesInMapTimeZone { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Reconstructs the CIMMapTimeDisplay with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapTimeDisplay FromJson(string json, JsonDeserializationSettings settings = null)
```
### FullTimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets the full time extent.</p>


```csharp
public TimeExtent FullTimeExtent { get; set; }
```
### HasLiveData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this map has live data.</p>


```csharp
public bool HasLiveData { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets the time reference.</p>


```csharp
public TimeReference TimeReference { get; set; }
```
### TimeRelation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets the time relation.</p>


```csharp
public esriTimeRelation TimeRelation { get; set; }
```
### TimeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets the time value.</p>


```csharp
public TimeValue TimeValue { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapTimeDisplay and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UniqueTimes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Gets or sets a cached set of unique OLE date values. Expected to be in the CIMMapTimeDisplay's TimeReference.</p>


```csharp
public double[] UniqueTimes { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTimeDisplay.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


