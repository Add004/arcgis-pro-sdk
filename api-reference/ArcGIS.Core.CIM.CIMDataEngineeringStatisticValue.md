# CIMDataEngineeringStatisticValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Contains a statistic value.</p>


## Object Signature

```csharp
public class CIMDataEngineeringStatisticValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDataEngineeringStatisticValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Contains a statistic value.</p>


```csharp
public CIMDataEngineeringStatisticValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDataEngineeringStatisticValue.</p>


```csharp
public CIMDataEngineeringStatisticValue Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Reconstructs the CIMDataEngineeringStatisticValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMDataEngineeringStatisticValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StatisticType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Gets or sets the statistic type.</p>


```csharp
public DataEngineeringStatType StatisticType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDataEngineeringStatisticValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Gets or sets statistic Value.</p>


```csharp
public object Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


