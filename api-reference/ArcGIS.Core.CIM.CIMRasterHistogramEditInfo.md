# CIMRasterHistogramEditInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Represents raster histogram custom stretch edit info.</p>


## Object Signature

```csharp
public class CIMRasterHistogramEditInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterHistogramEditInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Represents raster histogram custom stretch edit info.</p>


```csharp
public CIMRasterHistogramEditInfo()
```
### BreakPointsX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Gets or sets the X coordinate or input value at each breakpoint.</p>


```csharp
public int[] BreakPointsX { get; set; }
```
### BreakPointsY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Gets or sets the Y coordinate or input value at each breakpoint.</p>


```csharp
public int[] BreakPointsY { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterHistogramEditInfo.</p>


```csharp
public CIMRasterHistogramEditInfo Clone()
```
### EditType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Gets or sets the histogram edit type.</p>


```csharp
public RasterHistogramEditType EditType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterHistogramEditInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterHistogramEditInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterHistogramEditInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterHistogramEditInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


