# CIMRasterClassBreak

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Represents a raster class break.</p>


## Object Signature

```csharp
public class CIMRasterClassBreak : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterClassBreak()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Represents a raster class break.</p>


```csharp
public CIMRasterClassBreak()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterClassBreak.</p>


```csharp
public CIMRasterClassBreak Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Gets or sets the color for the raster class break.</p>


```csharp
public CIMColor Color { get; set; }
```
### CriticalBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is a critical break.</p>


```csharp
public bool CriticalBreak { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Gets or sets the description for the raster class break.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterClassBreak with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterClassBreak FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Gets or sets the label for the raster class break.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterClassBreak and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UpperBound

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Gets or sets the upper bound for the raster class break.</p>


```csharp
public double UpperBound { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassBreak.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


