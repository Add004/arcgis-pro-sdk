# CIMGeodatabaseErrorLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Represents GDB Error tables as a composite layer and draws the errors.</p>


## Object Signature

```csharp
public class CIMGeodatabaseErrorLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeodatabaseErrorLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Represents GDB Error tables as a composite layer and draws the errors.</p>


```csharp
public CIMGeodatabaseErrorLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeodatabaseErrorLayer.</p>


```csharp
public CIMGeodatabaseErrorLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMGeodatabaseErrorLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeodatabaseErrorLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the line layer in the Geodatabase Error layer.</p>


```csharp
public string LineLayer { get; set; }
```
### ObjectTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the object table in the Geodatabase Error layer.</p>


```csharp
public string ObjectTable { get; set; }
```
### PointLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the point layer in the Geodatabase Error layer.</p>


```csharp
public string PointLayer { get; set; }
```
### PolygonLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the polygon layer in the Geodatabase Error layer.</p>


```csharp
public string PolygonLayer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeodatabaseErrorLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WorkspaceConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the Geodatabase Errors data connection to the parent workspace.</p>


```csharp
public CIMWorkspaceConnection WorkspaceConnection { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeodatabaseErrorLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


