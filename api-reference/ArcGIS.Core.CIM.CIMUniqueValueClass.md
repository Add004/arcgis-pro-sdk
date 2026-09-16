# CIMUniqueValueClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Represents a unique value class.</p>


## Object Signature

```csharp
public class CIMUniqueValueClass : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMUniqueValueClass()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Represents a unique value class.</p>


```csharp
public CIMUniqueValueClass()
```
### AlternateSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets an array of symbol references that are intended to be used at specific scale ranges.</p>


```csharp
public CIMSymbolReference[] AlternateSymbols { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Creates a deep copy of CIMUniqueValueClass.</p>


```csharp
public CIMUniqueValueClass Clone()
```
### CustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the custom patch.</p>


```csharp
public CIMLegendPatch CustomPatch { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### Editable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this class is editable.</p>


```csharp
public bool Editable { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Reconstructs the CIMUniqueValueClass with a specified state from a JSON encoding.</p>


```csharp
public static CIMUniqueValueClass FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### Patch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the patch.</p>


```csharp
public PatchShape Patch { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMUniqueValueClass and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the values this class corresponds to.</p>


```csharp
public CIMUniqueValue[] Values { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this class is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueClass.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


