# CIMRasterBandDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Represents a raster band data connection.</p>


## Object Signature

```csharp
public class CIMRasterBandDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterBandDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Represents a raster band data connection.</p>


```csharp
public CIMRasterBandDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterBandDataConnection.</p>


```csharp
public CIMRasterBandDataConnection Clone()
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterBandDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterBandDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### RasterBandName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Gets or sets the raster band name.</p>


```csharp
public string RasterBandName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterBandDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterBandDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


