# CIMStreamServiceDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Represents a stream service data connection.</p>


## Object Signature

```csharp
public class CIMStreamServiceDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStreamServiceDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Represents a stream service data connection.</p>


```csharp
public CIMStreamServiceDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStreamServiceDataConnection.</p>


```csharp
public CIMStreamServiceDataConnection Clone()
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### FeatureExpirationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Gets or sets feature expiration method used at dataset level.</p>


```csharp
public FeatureExpirationMethod FeatureExpirationMethod { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMStreamServiceDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMStreamServiceDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumFeatureAge

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Gets or sets the maximum age for each feature before the feature is discarded.</p>


```csharp
public long MaximumFeatureAge { get; set; }
```
### MaximumFeatureCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Gets or sets the maximum number of features that are held in memory before features are discarded.</p>


```csharp
public long MaximumFeatureCount { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStreamServiceDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStreamServiceDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


