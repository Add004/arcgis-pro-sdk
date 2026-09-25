# CIMFormTimeInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Represents a time picker form input.</p>


## Object Signature

```csharp
public class CIMFormTimeInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormTimeInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Represents a time picker form input.</p>


```csharp
public CIMFormTimeInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormTimeInput.</p>


```csharp
public CIMFormTimeInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormTimeInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormTimeInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Gets or sets the maximum time to allow. Only the time portion of the timestamp is used.</p>


```csharp
public TimestampOffset Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Gets or sets the minimum time to allow. Only the time portion of the timestamp is used.</p>


```csharp
public TimestampOffset Min { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Gets or sets the resolution identifier. The default value is Minutes.</p>


```csharp
public FormTimeInputResolution TimeResolution { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormTimeInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimeInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


