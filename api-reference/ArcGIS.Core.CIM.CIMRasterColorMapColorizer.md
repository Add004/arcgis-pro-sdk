# CIMRasterColorMapColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Represents a raster color map colorizer.</p>


## Object Signature

```csharp
public class CIMRasterColorMapColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterColorMapColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Represents a raster color map colorizer.</p>


```csharp
public CIMRasterColorMapColorizer()
```
### BandID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Gets or sets the band ID.</p>


```csharp
public int BandID { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterColorMapColorizer.</p>


```csharp
public CIMRasterColorMapColorizer Clone()
```
### Colors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Gets or sets array of colors.</p>


```csharp
public CIMColor[] Colors { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterColorMapColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterColorMapColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Labels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Gets or sets the color labels as a string array.</p>


```csharp
public string[] Labels { get; set; }
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Gets or sets maximum value.</p>


```csharp
public int Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Gets or sets minimum value.</p>


```csharp
public int Min { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Gets or sets the number format.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterColorMapColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Gets or sets the array of values.</p>


```csharp
public int[] Values { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorMapColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


