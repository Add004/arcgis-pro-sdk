# CIMLatLonFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Represents a latitude and longitude format.</p>


## Object Signature

```csharp
public class CIMLatLonFormat : CIMNumericFormatBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLatLonFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Represents a latitude and longitude format.</p>


```csharp
public CIMLatLonFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLatLonFormat.</p>


```csharp
public CIMLatLonFormat Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMLatLonFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMLatLonFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsLatitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a formatted number is a latitude or not.</p>


```csharp
public bool IsLatitude { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowDirections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a directional letter (N-S-E-W) is appended to the formatted number.</p>


```csharp
public bool ShowDirections { get; set; }
```
### ShowZeroMinutes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether zero minutes are included in formatted output.</p>


```csharp
public bool ShowZeroMinutes { get; set; }
```
### ShowZeroSeconds

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether zero seconds are included in formatted output.</p>


```csharp
public bool ShowZeroSeconds { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLatLonFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLatLonFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


