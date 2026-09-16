# CIMUtilityNetworkLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Represents a utility network layer.</p>


## Object Signature

```csharp
public class CIMUtilityNetworkLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMUtilityNetworkLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Represents a utility network layer.</p>


```csharp
public CIMUtilityNetworkLayer()
```
### ActiveTraceConfigurations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the active trace configurations.</p>


```csharp
public CIMNetworkTraceConfiguration[] ActiveTraceConfigurations { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMUtilityNetworkLayer.</p>


```csharp
public CIMUtilityNetworkLayer Clone()
```
### ConnectivityAssociationSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the connectivity associations of the utility network.</p>


```csharp
public CIMSymbolReference ConnectivityAssociationSymbol { get; set; }
```
### ContainerAssociationSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the container associations of the utility network.</p>


```csharp
public CIMSymbolReference ContainerAssociationSymbol { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DirtyAreaLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the dirty area layer.</p>


```csharp
public string DirtyAreaLayer { get; set; }
```
### DirtyObjectsTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the dirty objects table in the utility network layer.</p>


```csharp
public string DirtyObjectsTable { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMUtilityNetworkLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMUtilityNetworkLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineErrorLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the line error layer.</p>


```csharp
public string LineErrorLayer { get; set; }
```
### PointErrorLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the point error layer.</p>


```csharp
public string PointErrorLayer { get; set; }
```
### PolygonErrorLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the polygon error layer.</p>


```csharp
public string PolygonErrorLayer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### StructuralAttachmentAssociationSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the structural attachment associations of the utility network.</p>


```csharp
public CIMSymbolReference StructuralAttachmentAssociationSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMUtilityNetworkLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


