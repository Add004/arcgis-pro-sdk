# CIMNetCDFRasterDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Represents a NetCDF raster data connection.</p>


## Object Signature

```csharp
public class CIMNetCDFRasterDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetCDFRasterDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Represents a NetCDF raster data connection.</p>


```csharp
public CIMNetCDFRasterDataConnection()
```
### BandDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the band dimension.</p>


```csharp
public string BandDimension { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetCDFRasterDataConnection.</p>


```csharp
public CIMNetCDFRasterDataConnection Clone()
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the extent.</p>


```csharp
public Envelope Extent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMNetCDFRasterDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetCDFRasterDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### InvertRows

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to invert rows.</p>


```csharp
public bool InvertRows { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SelectedDimensionIndexes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the selected dimension indexes.</p>


```csharp
public int[] SelectedDimensionIndexes { get; set; }
```
### SelectedDimensionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the selected dimension values.</p>


```csharp
public object[] SelectedDimensionValues { get; set; }
```
### SelectedDimensions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the selected dimensions.</p>


```csharp
public string[] SelectedDimensions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetCDFRasterDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Variable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the variable.</p>


```csharp
public string Variable { get; set; }
```
### VerticalDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the vertical dimension.</p>


```csharp
public string VerticalDimension { get; set; }
```
### VerticalDimensionUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the vertical dimension unit.</p>


```csharp
public string VerticalDimensionUnit { get; set; }
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the X dimension.</p>


```csharp
public string XDimension { get; set; }
```
### YDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFRasterDataConnection.yml" sourcestartlinenumber="1">Gets or sets the Y dimension.</p>


```csharp
public string YDimension { get; set; }
```


