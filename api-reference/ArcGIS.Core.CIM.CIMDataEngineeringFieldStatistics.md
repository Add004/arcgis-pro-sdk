# CIMDataEngineeringFieldStatistics

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Contains the field statistics.</p>


## Object Signature

```csharp
public class CIMDataEngineeringFieldStatistics : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDataEngineeringFieldStatistics()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Contains the field statistics.</p>


```csharp
public CIMDataEngineeringFieldStatistics()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDataEngineeringFieldStatistics.</p>


```csharp
public CIMDataEngineeringFieldStatistics Clone()
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Gets or sets field name.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Reconstructs the CIMDataEngineeringFieldStatistics with a specified state from a JSON encoding.</p>


```csharp
public static CIMDataEngineeringFieldStatistics FromJson(string json, JsonDeserializationSettings settings = null)
```
### PreviewChart

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Gets or sets the preview chart.</p>


```csharp
public CIMDataEngineeringPreviewChart PreviewChart { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDataEngineeringFieldStatistics and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TreatFieldAs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Gets or sets an option for treating a field as another
statistic type.</p>


```csharp
public DataEngineeringTreatFieldAsType TreatFieldAs { get; set; }
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Gets or sets statistic values.</p>


```csharp
public CIMDataEngineeringStatisticValue[] Values { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringFieldStatistics.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


