# CIMStatisticalDataCollectionInputPropertiesCalculator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputPropertiesCalculator.yml" sourcestartlinenumber="1">Statistical Data Collection calculator for accessing properties of input features, e.g. Area of polygonal input.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollectionInputPropertiesCalculator : CIMStatisticalDataCollectionCalculator, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionInputPropertiesCalculator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputPropertiesCalculator.yml" sourcestartlinenumber="1">Statistical Data Collection calculator for accessing properties of input features, e.g. Area of polygonal input.</p>


```csharp
public CIMStatisticalDataCollectionInputPropertiesCalculator()
```
### Area

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputPropertiesCalculator.yml" sourcestartlinenumber="1">Gets or sets the area property. If this property is not null, the geodesic area of the input feature will be calculated.</p>


```csharp
public CIMStatisticalDataCollectionInputAreaProperty Area { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputPropertiesCalculator.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollectionInputPropertiesCalculator.</p>


```csharp
public CIMStatisticalDataCollectionInputPropertiesCalculator Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputPropertiesCalculator.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollectionInputPropertiesCalculator with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollectionInputPropertiesCalculator FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputPropertiesCalculator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputPropertiesCalculator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollectionInputPropertiesCalculator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputPropertiesCalculator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


