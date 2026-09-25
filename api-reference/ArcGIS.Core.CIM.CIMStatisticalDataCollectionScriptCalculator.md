# CIMStatisticalDataCollectionScriptCalculator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionScriptCalculator.yml" sourcestartlinenumber="1">Statistical data collection calculator based on a scripts that use fields from other calculators.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollectionScriptCalculator : CIMStatisticalDataCollectionCalculator, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionScriptCalculator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionScriptCalculator.yml" sourcestartlinenumber="1">Statistical data collection calculator based on a scripts that use fields from other calculators.</p>


```csharp
public CIMStatisticalDataCollectionScriptCalculator()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionScriptCalculator.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollectionScriptCalculator.</p>


```csharp
public CIMStatisticalDataCollectionScriptCalculator Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionScriptCalculator.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollectionScriptCalculator with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollectionScriptCalculator FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionScriptCalculator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Scripts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionScriptCalculator.yml" sourcestartlinenumber="1">Gets or sets the scripts of the calculator.</p>


```csharp
public CIMStatisticalDataCollectionField[] Scripts { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionScriptCalculator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollectionScriptCalculator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionScriptCalculator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


