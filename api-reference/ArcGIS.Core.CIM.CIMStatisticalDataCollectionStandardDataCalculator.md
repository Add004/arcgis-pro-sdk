# CIMStatisticalDataCollectionStandardDataCalculator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Statistical data collection calculator based on a standard local data.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollectionStandardDataCalculator : CIMStatisticalDataCollectionCalculator, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionStandardDataCalculator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Statistical data collection calculator based on a standard local data.</p>


```csharp
public CIMStatisticalDataCollectionStandardDataCalculator()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollectionStandardDataCalculator.</p>


```csharp
public CIMStatisticalDataCollectionStandardDataCalculator Clone()
```
### DatasetID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Gets or sets the DatasetID which is used for getting the information about which points layer will be available and which apportionment methods will be used.
For example, for US 2019 dataset it will be ID of the dataset: &quot;USA_ESRI_2019&quot;.</p>


```csharp
public string DatasetID { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollectionStandardDataCalculator with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollectionStandardDataCalculator FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollectionStandardDataCalculator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Variables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Gets or sets the variables of the calculator.</p>


```csharp
public CIMStatisticalDataCollectionStandardVariable[] Variables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardDataCalculator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


