# CIMRasterUniqueValueClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Represents a raster unique value class.</p>


## Object Signature

```csharp
public class CIMRasterUniqueValueClass : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterUniqueValueClass()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Represents a raster unique value class.</p>


```csharp
public CIMRasterUniqueValueClass()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterUniqueValueClass.</p>


```csharp
public CIMRasterUniqueValueClass Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the class color.</p>


```csharp
public CIMColor Color { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the class description.</p>


```csharp
public string Description { get; set; }
```
### Editable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this class is editable.</p>


```csharp
public bool Editable { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterUniqueValueClass with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterUniqueValueClass FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the class label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterUniqueValueClass and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets the class values as a string array.</p>


```csharp
public string[] Values { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this class is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueClass.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


