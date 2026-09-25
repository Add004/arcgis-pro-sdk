# CIMNetCDFStandardDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Represents a NetCDF standard data connection.</p>


## Object Signature

```csharp
public class CIMNetCDFStandardDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetCDFStandardDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Represents a NetCDF standard data connection.</p>


```csharp
public CIMNetCDFStandardDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetCDFStandardDataConnection.</p>


```csharp
public CIMNetCDFStandardDataConnection Clone()
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMNetCDFStandardDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetCDFStandardDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### MDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the M dimension.</p>


```csharp
public string MDimension { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RowDimensionList

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the row dimension list.</p>


```csharp
public string[] RowDimensionList { get; set; }
```
### SelectedDimensionIndexes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the selected dimension indexes.</p>


```csharp
public int[] SelectedDimensionIndexes { get; set; }
```
### SelectedDimensionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the selected dimension values.</p>


```csharp
public object[] SelectedDimensionValues { get; set; }
```
### SelectedDimensions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the selected dimensions.</p>


```csharp
public string[] SelectedDimensions { get; set; }
```
### SelectedVolume

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the selected volume in a multi-volume dataset.</p>


```csharp
public string SelectedVolume { get; set; }
```
### ShapeFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the shape field name.</p>


```csharp
public string ShapeFieldName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetCDFStandardDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VariableList

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the variable list.</p>


```csharp
public string[] VariableList { get; set; }
```
### VerticalDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the vertical dimension.</p>


```csharp
public string VerticalDimension { get; set; }
```
### VerticalDimensionUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the vertical dimension unit.</p>


```csharp
public string VerticalDimensionUnit { get; set; }
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the X dimension.</p>


```csharp
public string XDimension { get; set; }
```
### YDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the Y dimension.</p>


```csharp
public string YDimension { get; set; }
```
### ZDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetCDFStandardDataConnection.yml" sourcestartlinenumber="1">Gets or sets the Z dimension.</p>


```csharp
public string ZDimension { get; set; }
```


