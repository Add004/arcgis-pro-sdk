# CIMAuxiliaryRasterProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Represents auxiliary raster properties.</p>


## Object Signature

```csharp
public class CIMAuxiliaryRasterProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAuxiliaryRasterProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Represents auxiliary raster properties.</p>


```csharp
public CIMAuxiliaryRasterProperties()
```
### BandIndexes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Gets or sets a long array of the band indexes.</p>


```csharp
public int[] BandIndexes { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAuxiliaryRasterProperties.</p>


```csharp
public CIMAuxiliaryRasterProperties Clone()
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Gets or sets the extent.</p>


```csharp
public Envelope Extent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMAuxiliaryRasterProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMAuxiliaryRasterProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Gets or sets the height.</p>


```csharp
public int Height { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAuxiliaryRasterProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Gets or sets the width.</p>


```csharp
public int Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAuxiliaryRasterProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


