# CIMRasterDiscreteColorColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Represents a raster discrete color colorizer.</p>


## Object Signature

```csharp
public class CIMRasterDiscreteColorColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterDiscreteColorColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Represents a raster discrete color colorizer.</p>


```csharp
public CIMRasterDiscreteColorColorizer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterDiscreteColorColorizer.</p>


```csharp
public CIMRasterDiscreteColorColorizer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### Colormap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Gets or sets the colormap.</p>


```csharp
public RasterColormap Colormap { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterDiscreteColorColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterDiscreteColorColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### NumColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Gets or sets the number of colors.</p>


```csharp
public int NumColors { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterDiscreteColorColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDiscreteColorColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


