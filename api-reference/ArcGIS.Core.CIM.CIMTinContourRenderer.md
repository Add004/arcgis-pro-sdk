# CIMTinContourRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Represents a TIN contour renderer.</p>


## Object Signature

```csharp
public class CIMTinContourRenderer : CIMTinRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTinContourRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Represents a TIN contour renderer.</p>


```csharp
public CIMTinContourRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTinContourRenderer.</p>


```csharp
public CIMTinContourRenderer Clone()
```
### ContourDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the contour description.</p>


```csharp
public string ContourDescription { get; set; }
```
### ContourInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the contour interval.</p>


```csharp
public double ContourInterval { get; set; }
```
### ContourIntervalScaleBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the contour interval scale breaks.
The scale breaks should be ordered from the smallest scale to the largest. The last scale break's upper bound
will always be treated as 0, indicating no upper bound.</p>


```csharp
public CIMContourIntervalScaleBreak[] ContourIntervalScaleBreaks { get; set; }
```
### ContourLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the contour label.</p>


```csharp
public string ContourLabel { get; set; }
```
### ContourSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the contour symbol.</p>


```csharp
public CIMSymbolReference ContourSymbol { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMTinContourRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTinContourRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### IndexContourDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the index contour description.</p>


```csharp
public string IndexContourDescription { get; set; }
```
### IndexContourFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the index contour factor.</p>


```csharp
public int IndexContourFactor { get; set; }
```
### IndexContourLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the index contour label.</p>


```csharp
public string IndexContourLabel { get; set; }
```
### IndexContourSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the index contour symbol.</p>


```csharp
public CIMSymbolReference IndexContourSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceContourHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets the reference contour height.</p>


```csharp
public double ReferenceContourHeight { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTinContourRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseIntervalScaleBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether scale-dependent intervals are used.
If true, <xref href="ArcGIS.Core.CIM.CIMTinContourRenderer.ContourIntervalScaleBreaks" data-throw-if-not-resolved="false"></xref> are used; if false, <xref href="ArcGIS.Core.CIM.CIMTinContourRenderer.ContourInterval" data-throw-if-not-resolved="false"></xref> is used at
all scales.</p>


```csharp
public bool UseIntervalScaleBreaks { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinContourRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


