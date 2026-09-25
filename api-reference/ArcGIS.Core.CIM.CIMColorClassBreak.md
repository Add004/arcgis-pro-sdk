# CIMColorClassBreak

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Represents a color class break.</p>


## Object Signature

```csharp
public class CIMColorClassBreak : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMColorClassBreak()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Represents a color class break.</p>


```csharp
public CIMColorClassBreak()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Creates a deep copy of CIMColorClassBreak.</p>


```csharp
public CIMColorClassBreak Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Gets or sets the color for the color class break.</p>


```csharp
public CIMColor Color { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Gets or sets the description for the color class break.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Reconstructs the CIMColorClassBreak with a specified state from a JSON encoding.</p>


```csharp
public static CIMColorClassBreak FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Gets or sets the label for the color class break.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMColorClassBreak and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UpperBound

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Gets or sets the upper bound for the color class break.</p>


```csharp
public double UpperBound { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreak.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


