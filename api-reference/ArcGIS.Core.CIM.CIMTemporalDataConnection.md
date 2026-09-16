# CIMTemporalDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Represents a temporal data connection.</p>


## Object Signature

```csharp
public class CIMTemporalDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTemporalDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Represents a temporal data connection.</p>


```csharp
public CIMTemporalDataConnection()
```
### CachingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the caching mode.</p>


```csharp
public TemporalFeatureClassCachingMode CachingMode { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTemporalDataConnection.</p>


```csharp
public CIMTemporalDataConnection Clone()
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### EndTimeField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the end time field.</p>


```csharp
public string EndTimeField { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMTemporalDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMTemporalDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartTimeField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the start time field.</p>


```csharp
public string StartTimeField { get; set; }
```
### TimeFieldAmFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the custom string representation of the AM symbol.</p>


```csharp
public string TimeFieldAmFormat { get; set; }
```
### TimeFieldLocaleID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the time field locale ID.</p>


```csharp
public int TimeFieldLocaleID { get; set; }
```
### TimeFieldPmFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the custom string representation of the PM symbol.</p>


```csharp
public string TimeFieldPmFormat { get; set; }
```
### TimeValueFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the time value format.</p>


```csharp
public string TimeValueFormat { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTemporalDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrackIDField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the track ID field.</p>


```csharp
public string TrackIDField { get; set; }
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTemporalDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


