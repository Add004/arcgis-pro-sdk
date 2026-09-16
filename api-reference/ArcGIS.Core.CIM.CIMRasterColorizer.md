# CIMRasterColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Represents a raster colorizer.</p>


## Object Signature

```csharp
public abstract class CIMRasterColorizer : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Represents a raster colorizer.</p>


```csharp
protected CIMRasterColorizer()
```
### Brightness

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Gets or sets the brightness value.</p>


```csharp
public int Brightness { get; set; }
```
### Contrast

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Gets or sets the contrast value.</p>


```csharp
public int Contrast { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Gets or sets the no data color.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ResamplingType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Gets or sets the raster resampling type.</p>


```csharp
public RasterResamplingType ResamplingType { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


