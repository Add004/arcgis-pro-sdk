# CIMClassBreak

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Represents a class break.</p>


## Object Signature

```csharp
public class CIMClassBreak : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMClassBreak()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Represents a class break.</p>


```csharp
public CIMClassBreak()
```
### AlternateSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Gets or sets an array of symbol references that are intended to be used at specific scale ranges.</p>


```csharp
public CIMSymbolReference[] AlternateSymbols { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Creates a deep copy of CIMClassBreak.</p>


```csharp
public CIMClassBreak Clone()
```
### CriticalBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is a critical break.</p>


```csharp
public bool CriticalBreak { get; set; }
```
### CustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Gets or sets the custom patch for this class.</p>


```csharp
public CIMLegendPatch CustomPatch { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Reconstructs the CIMClassBreak with a specified state from a JSON encoding.</p>


```csharp
public static CIMClassBreak FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### Patch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Gets or sets the patch shape for this class.</p>


```csharp
public PatchShape Patch { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Gets or sets the symbol for the class.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMClassBreak and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UpperBound

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Gets or sets the upper bound of the class.</p>


```csharp
public double UpperBound { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreak.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


