# CIMColorUniqueValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Represents a color unique value.</p>


## Object Signature

```csharp
public class CIMColorUniqueValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMColorUniqueValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Represents a color unique value.</p>


```csharp
public CIMColorUniqueValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMColorUniqueValue.</p>


```csharp
public CIMColorUniqueValue Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets the class color.</p>


```csharp
public CIMColor Color { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets the class description.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Reconstructs the CIMColorUniqueValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMColorUniqueValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets the class label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMColorUniqueValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets the class value as a string.</p>


```csharp
public string Value { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this class is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorUniqueValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


