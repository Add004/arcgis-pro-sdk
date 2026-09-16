# CIMStatisticalDataCollectionDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionDocument.yml" sourcestartlinenumber="1">Represents a document used for saving statistical data collections.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollectionDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionDocument.yml" sourcestartlinenumber="1">Represents a document used for saving statistical data collections.</p>


```csharp
public CIMStatisticalDataCollectionDocument()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollectionDocument.</p>


```csharp
public CIMStatisticalDataCollectionDocument Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollectionDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollectionDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StatisticalDataCollection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionDocument.yml" sourcestartlinenumber="1">Gets or sets the Statistical Data Collection.</p>


```csharp
public CIMStatisticalDataCollection StatisticalDataCollection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollectionDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


