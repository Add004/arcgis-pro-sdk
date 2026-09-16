# CIMAggregateField

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">A field holding the result of an aggregation of multiple field values.</p>


## Object Signature

```csharp
public class CIMAggregateField : CIMFieldDescription, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAggregateField()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">A field holding the result of an aggregation of multiple field values.</p>


```csharp
public CIMAggregateField()
```
### AggregatedFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">Gets or sets the field name on which the aggregation was done.</p>


```csharp
public string AggregatedFieldName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAggregateField.</p>


```csharp
public CIMAggregateField Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">Reconstructs the CIMAggregateField with a specified state from a JSON encoding.</p>


```csharp
public static CIMAggregateField FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StatisticType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">Gets or sets the type of statistic used to aggregate data.</p>


```csharp
public esriDataStatType StatisticType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAggregateField and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateField.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


