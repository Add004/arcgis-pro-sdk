# CIMRangeDimensionValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Represents a range dimension name and value pair used to define the multidimensional display definition for the current display slice.</p>


## Object Signature

```csharp
public class CIMRangeDimensionValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRangeDimensionValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Represents a range dimension name and value pair used to define the multidimensional display definition for the current display slice.</p>


```csharp
public CIMRangeDimensionValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRangeDimensionValue.</p>


```csharp
public CIMRangeDimensionValue Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Reconstructs the CIMRangeDimensionValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMRangeDimensionValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### RangeDimensionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the name of the dimension.</p>


```csharp
public string RangeDimensionName { get; set; }
```
### RangeDimensionValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the range dimension value.</p>


```csharp
public CIMRange RangeDimensionValue { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRangeDimensionValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDimensionValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


