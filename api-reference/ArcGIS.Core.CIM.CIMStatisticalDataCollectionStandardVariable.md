# CIMStatisticalDataCollectionStandardVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Represents a field of a statistical data collection that matches to an existing variable in referenced feature dataset.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollectionStandardVariable : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionStandardVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Represents a field of a statistical data collection that matches to an existing variable in referenced feature dataset.</p>


```csharp
public CIMStatisticalDataCollectionStandardVariable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollectionStandardVariable.</p>


```csharp
public CIMStatisticalDataCollectionStandardVariable Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollectionStandardVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollectionStandardVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Gets or sets the name of the variable.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowInDataBrowser

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the variable will be shown in the Data Browser control in ArcGIS Pro.</p>


```csharp
public bool ShowInDataBrowser { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollectionStandardVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionStandardVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


