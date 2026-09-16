# CIMTimeDataDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Represents a time data definition.</p>


## Object Signature

```csharp
public class CIMTimeDataDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimeDataDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Represents a time data definition.</p>


```csharp
public CIMTimeDataDefinition()
```
### ApplyTimeReferenceToAllFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the time reference applies to all date fields in the layer or only the fields driving time-awareness.</p>


```csharp
public bool ApplyTimeReferenceToAllFields { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimeDataDefinition.</p>


```csharp
public CIMTimeDataDefinition Clone()
```
### CustomTimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Gets or sets the custom time extent.</p>


```csharp
public TimeExtent CustomTimeExtent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMTimeDataDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimeDataDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### HasLiveData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this dataset has live data.</p>


```csharp
public bool HasLiveData { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeExtentCanChange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the data regularly changes, so the extent needs recalculated.</p>


```csharp
public bool TimeExtentCanChange { get; set; }
```
### TimeReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Gets or sets the time reference.</p>


```csharp
public TimeReference TimeReference { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimeDataDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use time for animation purposes.</p>


```csharp
public bool UseTime { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDataDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


