# CIMHuffModelCalibrationDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Represents a Huff Model calibration.</p>


## Object Signature

```csharp
public class CIMHuffModelCalibrationDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHuffModelCalibrationDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Represents a Huff Model calibration.</p>


```csharp
public CIMHuffModelCalibrationDocument()
```
### AttractivenessVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets attractiveness variables of Huff Model calibration.</p>


```csharp
public CIMHuffModelAttractivenessVariable[] AttractivenessVariables { get; set; }
```
### Author

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets author of Huff Model calibration.</p>


```csharp
public string Author { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHuffModelCalibrationDocument.</p>


```csharp
public CIMHuffModelCalibrationDocument Clone()
```
### CreationDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets creation date of Huff Model calibration.</p>


```csharp
public TimeInstant CreationDate { get; set; }
```
### CustomerWeightFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets customer weight field name used in Huff Model calibration.</p>


```csharp
public string CustomerWeightFieldName { get; set; }
```
### Customers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets customers dataset used in Huff Model calibration.</p>


```csharp
public CIMDataConnection Customers { get; set; }
```
### CustomersIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets customer ID field name used in Huff Model calibration.</p>


```csharp
public string CustomersIDFieldName { get; set; }
```
### DistanceParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets distance parameters of Huff Model calibration.</p>


```csharp
public CIMHuffModelDistanceParameters DistanceParameters { get; set; }
```
### Facilities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets facilities dataset used in Huff Model calibration.</p>


```csharp
public CIMDataConnection Facilities { get; set; }
```
### FacilitiesIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets facility ID field name used in Huff Model calibration.</p>


```csharp
public string FacilitiesIDFieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMHuffModelCalibrationDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMHuffModelCalibrationDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### LastRevisionDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets last revision date of Huff Model calibration.</p>


```csharp
public TimeInstant LastRevisionDate { get; set; }
```
### RMSError

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets RMS error of Huff Model calibration.</p>


```csharp
public double RMSError { get; set; }
```
### RMSErrorLinear

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets linearized RMS error of Huff Model calibration.</p>


```csharp
public double RMSErrorLinear { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SalesPotential

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets sales potential dataset used in Huff Model calibration.</p>


```csharp
public CIMDataConnection SalesPotential { get; set; }
```
### SalesPotentialIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Gets or sets sales potential ID field name used in Huff Model calibration.</p>


```csharp
public string SalesPotentialIDFieldName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHuffModelCalibrationDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelCalibrationDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


