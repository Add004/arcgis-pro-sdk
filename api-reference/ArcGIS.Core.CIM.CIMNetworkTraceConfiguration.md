# CIMNetworkTraceConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Represents a Trace Configuration.</p>


## Object Signature

```csharp
public class CIMNetworkTraceConfiguration : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkTraceConfiguration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Represents a Trace Configuration.</p>


```csharp
public CIMNetworkTraceConfiguration()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkTraceConfiguration.</p>


```csharp
public CIMNetworkTraceConfiguration Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkTraceConfiguration with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkTraceConfiguration FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Gets or sets global id of trace configuration.</p>


```csharp
public string ID { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Gets or sets the name of trace configuration.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkTraceConfiguration and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTraceConfiguration.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


