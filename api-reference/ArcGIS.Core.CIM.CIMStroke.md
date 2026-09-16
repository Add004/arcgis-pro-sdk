# CIMStroke

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Represents a stroke which defines how line geometry or the outline of polygon geometry is drawn.</p>


## Object Signature

```csharp
public abstract class CIMStroke : CIMSymbolLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStroke()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Represents a stroke which defines how line geometry or the outline of polygon geometry is drawn.</p>


```csharp
protected CIMStroke()
```
### Anchor3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Gets or sets the vertical anchor of the 3D line style applied to the stroke. This property is ignored for the Strip and Wall styles.</p>


```csharp
public Simple3DLineAnchor Anchor3D { get; set; }
```
### CapStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Gets or sets how the stroke should draw at the ends of the geometries.</p>


```csharp
public LineCapStyle CapStyle { get; set; }
```
### CloseCaps3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to close caps when drawing them in 3D. When set to false, the caps are hollow.</p>


```csharp
public bool CloseCaps3D { get; set; }
```
### Height3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Gets or sets the height. Used when the 3D line style is Rectangle.</p>


```csharp
public double Height3D { get; set; }
```
### JoinStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Gets or sets how the symbol is drawn at the stroke segment connections.</p>


```csharp
public LineJoinStyle JoinStyle { get; set; }
```
### LineStyle3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Gets or sets how strokes will be rendered in 3D.</p>


```csharp
public Simple3DLineStyle LineStyle3D { get; set; }
```
### MiterLimit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Gets or sets the maximum 'sharpness' that is allowed for Miter joins. If the spike created by the miter join exceeds the miter limit times the width of the stroke, the sharp angle will be clipped and rendered with a bevel join. This property is only applied to the symbol layer when the JoinType is set to Miter.</p>


```csharp
public double MiterLimit { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Gets or sets the width of the stroke.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStroke.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


