# CIMChartMarker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarker.yml" sourcestartlinenumber="1">Represents a chart marker, a marker used to display a chart.</p>


## Object Signature

```csharp
public abstract class CIMChartMarker : CIMMarker, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartMarker()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarker.yml" sourcestartlinenumber="1">Represents a chart marker, a marker used to display a chart.</p>


```csharp
protected CIMChartMarker()
```
### Display3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the chart with a 3D perspective.</p>


```csharp
public bool Display3D { get; set; }
```
### Parts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarker.yml" sourcestartlinenumber="1">Gets or sets the individual components of the chart marker.</p>


```csharp
public CIMChartPart[] Parts { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarker.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Thickness3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarker.yml" sourcestartlinenumber="1">Gets or sets the thickness or depth of a chart. Only applied when Display3D is true.</p>


```csharp
public double Thickness3D { get; set; }
```
### Tilt3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarker.yml" sourcestartlinenumber="1">Gets or sets the tilt (rotation around the X axis) of the chart. Only applied when Display3D is true.</p>


```csharp
public double Tilt3D { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarker.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


