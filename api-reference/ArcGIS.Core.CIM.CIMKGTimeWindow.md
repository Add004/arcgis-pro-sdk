# CIMKGTimeWindow

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Defines a window of time.</p>


## Object Signature

```csharp
public class CIMKGTimeWindow : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGTimeWindow()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Defines a window of time.</p>


```csharp
public CIMKGTimeWindow()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGTimeWindow.</p>


```csharp
public CIMKGTimeWindow Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Reconstructs the CIMKGTimeWindow with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGTimeWindow FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Gets or sets the maximum time. Can be null if no maximum time exists.</p>


```csharp
public TimestampOffset MaxTime { get; set; }
```
### MinTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Gets or sets the minimum time. Can be null if no minimum time exists.</p>


```csharp
public TimestampOffset MinTime { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGTimeWindow and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeWindow.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


