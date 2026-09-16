# CIMExtentIndicator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Represents an extent indicator which is used to display the visible extent of other map frames in an associated map frame.</p>


## Object Signature

```csharp
public class CIMExtentIndicator : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMExtentIndicator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Represents an extent indicator which is used to display the visible extent of other map frames in an associated map frame.</p>


```csharp
public CIMExtentIndicator()
```
### AvoidLabelConflict

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to avoid label conflict. Reserved for future implementation.</p>


```csharp
public bool AvoidLabelConflict { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Creates a deep copy of CIMExtentIndicator.</p>


```csharp
public CIMExtentIndicator Clone()
```
### CollapseSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets the minimum size of the extent indicator before symbolizing it as a point. Units in points.</p>


```csharp
public double CollapseSize { get; set; }
```
### ExtentIndicatorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets the extent indicator type. Reserved for future implementation at this time.</p>


```csharp
public ExtentIndicatorType ExtentIndicatorType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Reconstructs the CIMExtentIndicator with a specified state from a JSON encoding.</p>


```csharp
public static CIMExtentIndicator FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the extent indicator is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### LeaderSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets the leader symbol used to connect the associated extents.</p>


```csharp
public CIMSymbolReference LeaderSymbol { get; set; }
```
### LeaderType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets the leader style used to connect the associated extents.</p>


```csharp
public LeaderType LeaderType { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets the name of the extent indicator.</p>


```csharp
public string Name { get; set; }
```
### PointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets the point symbol used to symbolize an extent indicator.</p>


```csharp
public CIMSymbolReference PointSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceMapFrame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets the source map frame's extent to be displayed.</p>


```csharp
public string SourceMapFrame { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets the area symbol used to represent the extent indicator.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### SymbolizeExterior

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the area symbol should be applied outside the extent.</p>


```csharp
public bool SymbolizeExterior { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMExtentIndicator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtentIndicator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


