# CIMTrackingServerDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Represents a tracking server data connection.</p>


## Object Signature

```csharp
public class CIMTrackingServerDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTrackingServerDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Represents a tracking server data connection.</p>


```csharp
public CIMTrackingServerDataConnection()
```
### AutoPurge

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to automatically purge data.</p>


```csharp
public bool AutoPurge { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTrackingServerDataConnection.</p>


```csharp
public CIMTrackingServerDataConnection Clone()
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMTrackingServerDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMTrackingServerDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### KeepPerTrack

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the minimum number of features to keep per track.</p>


```csharp
public int KeepPerTrack { get; set; }
```
### PurgePercentage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the percentage of the maximum allowed number of records to delete when the purge occurs.</p>


```csharp
public double PurgePercentage { get; set; }
```
### PurgeRule

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the purge rule.</p>


```csharp
public TemporalFeatureClassPurgeRule PurgeRule { get; set; }
```
### PurgeThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the purge threshold.</p>


```csharp
public int PurgeThreshold { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTrackingServerDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrackingServerDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


