# CIMNestedLegendItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Represents a nested legend item in a legend.</p>


## Object Signature

```csharp
public class CIMNestedLegendItem : CIMLegendItem, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNestedLegendItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Represents a nested legend item in a legend.</p>


```csharp
public CIMNestedLegendItem()
```
### Arrangement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Gets or sets the Arrangement.</p>


```csharp
public LegendItemArrangement Arrangement { get; set; }
```
### AutoLayout

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to automatically layout the legend item.</p>


```csharp
public bool AutoLayout { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNestedLegendItem.</p>


```csharp
public CIMNestedLegendItem Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Reconstructs the CIMNestedLegendItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMNestedLegendItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### LabelEnds

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the ends of a nested legend item should be labeled.</p>


```csharp
public bool LabelEnds { get; set; }
```
### LineLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Gets or sets the line length for a legend item leader.</p>


```csharp
public double LineLength { get; set; }
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Gets or sets the line symbol for a legend item leader.</p>


```csharp
public CIMSymbolReference LineSymbol { get; set; }
```
### OutlineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Gets or sets the outline symbol for the nested legend item.</p>


```csharp
public CIMSymbolReference OutlineSymbol { get; set; }
```
### PatchAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Gets or sets the patch alignment for a nested legend item.</p>


```csharp
public HorizontalAlignment PatchAlignment { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowOutlines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether outlines should be displayed for a nested legend item.</p>


```csharp
public bool ShowOutlines { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNestedLegendItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNestedLegendItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


