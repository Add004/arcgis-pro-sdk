# CIMTraceNetworkLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Represents a trace network layer.</p>


## Object Signature

```csharp
public class CIMTraceNetworkLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTraceNetworkLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Represents a trace network layer.</p>


```csharp
public CIMTraceNetworkLayer()
```
### ActiveTraceConfigurations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the active trace configurations.</p>


```csharp
public CIMNetworkTraceConfiguration[] ActiveTraceConfigurations { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTraceNetworkLayer.</p>


```csharp
public CIMTraceNetworkLayer Clone()
```
### ConnectivityAssociationSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the connectivity associations of the trace network.</p>


```csharp
public CIMSymbolReference ConnectivityAssociationSymbol { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DirtyAreaLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the dirty area layer.</p>


```csharp
public string DirtyAreaLayer { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMTraceNetworkLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTraceNetworkLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineErrorLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the line error layer.</p>


```csharp
public string LineErrorLayer { get; set; }
```
### PointErrorLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the point error layer.</p>


```csharp
public string PointErrorLayer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SystemJunctionsLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the junction layer.</p>


```csharp
public string SystemJunctionsLayer { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTraceNetworkLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraceNetworkLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


