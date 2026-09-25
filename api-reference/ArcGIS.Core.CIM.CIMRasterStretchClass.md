# CIMRasterStretchClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Represents a raster stretch class.</p>


## Object Signature

```csharp
public class CIMRasterStretchClass : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterStretchClass()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Represents a raster stretch class.</p>


```csharp
public CIMRasterStretchClass()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterStretchClass.</p>


```csharp
public CIMRasterStretchClass Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterStretchClass with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterStretchClass FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Gets or sets the raster stretch class label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterStretchClass and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Gets or sets the raster stretch class value.</p>


```csharp
public double Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchClass.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


