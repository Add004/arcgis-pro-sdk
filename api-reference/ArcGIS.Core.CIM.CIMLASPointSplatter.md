# CIMLASPointSplatter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Represents a LAS point splatter.</p>


## Object Signature

```csharp
public class CIMLASPointSplatter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLASPointSplatter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Represents a LAS point splatter.</p>


```csharp
public CIMLASPointSplatter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLASPointSplatter.</p>


```csharp
public CIMLASPointSplatter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Reconstructs the CIMLASPointSplatter with a specified state from a JSON encoding.</p>


```csharp
public static CIMLASPointSplatter FromJson(string json, JsonDeserializationSettings settings = null)
```
### PointSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Gets or sets the size of rendered LAS points when Fixed or RealWorld point sizing are used. If real-world
sizing is used, the value is represented in meters; otherwise the value is in screen-based points.</p>


```csharp
public double PointSize { get; set; }
```
### PointSizingMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Gets or sets the method used to determine the rendering size of LAS points.
In 2D, only FixedAutoScale is supported.</p>


```csharp
public LASPointSizingMethod PointSizingMethod { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SplatMinimumSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Gets or sets splat minimum size.</p>


```csharp
public double SplatMinimumSize { get; set; }
```
### SplatScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Gets or sets splat scale.</p>


```csharp
public double SplatScale { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLASPointSplatter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSplatHighlight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use splat highlighting.</p>


```csharp
public bool UseSplatHighlight { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointSplatter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


