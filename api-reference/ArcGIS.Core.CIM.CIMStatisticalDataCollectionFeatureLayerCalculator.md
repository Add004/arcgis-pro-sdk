# CIMStatisticalDataCollectionFeatureLayerCalculator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Statistical data collection calculator based on a feature layer.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollectionFeatureLayerCalculator : CIMStatisticalDataCollectionCalculator, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionFeatureLayerCalculator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Statistical data collection calculator based on a feature layer.</p>


```csharp
public CIMStatisticalDataCollectionFeatureLayerCalculator()
```
### ApportionmentDatasetConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Gets or sets the data connection to apportionment dataset. This property is optional.</p>


```csharp
public CIMDataConnection ApportionmentDatasetConnection { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollectionFeatureLayerCalculator.</p>


```csharp
public CIMStatisticalDataCollectionFeatureLayerCalculator Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Gets or sets the data connection to the source.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DatasetID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Gets or sets the DatasetID which is used for getting the information about which points layer will be available and which apportionment methods will be used. If DatasetID is empty, only Area Apportionment method is available.</p>


```csharp
public string DatasetID { get; set; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Gets or sets the regular fields of the calculator.</p>


```csharp
public CIMStatisticalDataCollectionField[] Fields { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollectionFeatureLayerCalculator with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollectionFeatureLayerCalculator FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollectionFeatureLayerCalculator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionFeatureLayerCalculator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


