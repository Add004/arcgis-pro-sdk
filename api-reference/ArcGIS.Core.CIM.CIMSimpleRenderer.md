# CIMSimpleRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Represents a simple renderer.</p>


## Object Signature

```csharp
public class CIMSimpleRenderer : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSimpleRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Represents a simple renderer.</p>


```csharp
public CIMSimpleRenderer()
```
### AlternateSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets an array of symbol references that are intended to be used at specific scale ranges.</p>


```csharp
public CIMSymbolReference[] AlternateSymbols { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSimpleRenderer.</p>


```csharp
public CIMSimpleRenderer Clone()
```
### CustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the custom patch.</p>


```csharp
public CIMLegendPatch CustomPatch { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMSimpleRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMSimpleRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend label.</p>


```csharp
public string Label { get; set; }
```
### Patch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the patch.</p>


```csharp
public PatchShape Patch { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SampleSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum number of records to sample.</p>


```csharp
public int SampleSize { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSimpleRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisualVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the visual variables.</p>


```csharp
public CIMVisualVariable[] VisualVariables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


