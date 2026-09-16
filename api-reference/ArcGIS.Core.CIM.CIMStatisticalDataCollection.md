# CIMStatisticalDataCollection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">A statistical data collection is used by the Business Analyst to organize and present data that can be aggregated by the enrich functionality. This is not the storage of the data, it is metadata about the data that describes how data will be aggregated by Business Analyst. Currently, data can be calculated by defining what data collections and analysis variables are needed in the output for a given input features.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollection : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">A statistical data collection is used by the Business Analyst to organize and present data that can be aggregated by the enrich functionality. This is not the storage of the data, it is metadata about the data that describes how data will be aggregated by Business Analyst. Currently, data can be calculated by defining what data collections and analysis variables are needed in the output for a given input features.</p>


```csharp
public CIMStatisticalDataCollection()
```
### Author

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets author of the data collection.</p>


```csharp
public string Author { get; set; }
```
### Calculators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets the Calculators of the data collection.</p>


```csharp
public CIMStatisticalDataCollectionCalculator[] Calculators { get; set; }
```
### Categories

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets levels of categories the data collection. Used to show the data collection in the Data Browser.</p>


```csharp
public string[] Categories { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollection.</p>


```csharp
public CIMStatisticalDataCollection Clone()
```
### Countries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets list of countries for data collection. Use to filter data collections by country.</p>


```csharp
public string[] Countries { get; set; }
```
### CreationDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets creation date of the data collection.</p>


```csharp
public TimeInstant CreationDate { get; set; }
```
### DataVintage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets vintage of used data (for example, &quot;Q3_2018&quot;).</p>


```csharp
public string DataVintage { get; set; }
```
### DataVintageDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets description of used data (&quot;2018 US Data Update&quot;).</p>


```csharp
public string DataVintageDescription { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollection with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollection FromJson(string json, JsonDeserializationSettings settings = null)
```
### Icon

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets data collection image.</p>


```csharp
public string Icon { get; set; }
```
### Keywords

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets keywords for the data collection.</p>


```csharp
public string[] Keywords { get; set; }
```
### LastRevisionDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets last revision date of the data collection.</p>


```csharp
public TimeInstant LastRevisionDate { get; set; }
```
### LongDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets long description of the data collection.</p>


```csharp
public string LongDescription { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets the Name of the data collection.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShortDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Gets or sets short description of the data collection.</p>


```csharp
public string ShortDescription { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


