# CIMLinkChartNodeDrawingInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Represents the link chart node drawing information.</p>


## Object Signature

```csharp
public class CIMLinkChartNodeDrawingInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartNodeDrawingInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Represents the link chart node drawing information.</p>


```csharp
public CIMLinkChartNodeDrawingInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartNodeDrawingInfo.</p>


```csharp
public CIMLinkChartNodeDrawingInfo Clone()
```
### CollapseDuplicates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the entity whether duplicate node values are consolidated. The result is one node for multiple values.</p>


```csharp
public bool CollapseDuplicates { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartNodeDrawingInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartNodeDrawingInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### NodeSymbology

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the entity symbology preference.</p>


```csharp
public LinkChartSymbolizationSource NodeSymbology { get; set; }
```
### OverrideOverviewSymbolColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the overview symbol color is calculated or specified.</p>


```csharp
public bool OverrideOverviewSymbolColor { get; set; }
```
### OverrideSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the override symbol.</p>


```csharp
public CIMSymbolReference OverrideSymbol { get; set; }
```
### OverviewSymbolColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the override overview symbol color.</p>


```csharp
public CIMColor OverviewSymbolColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowNodeFrames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the node frames are shown.</p>


```csharp
public bool ShowNodeFrames { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartNodeDrawingInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartNodeDrawingInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


