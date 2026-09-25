# CIMHorizontalBarLegendItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Represents a horizontal bar legend item.</p>


## Object Signature

```csharp
public class CIMHorizontalBarLegendItem : CIMLegendItem, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHorizontalBarLegendItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Represents a horizontal bar legend item.</p>


```csharp
public CIMHorizontalBarLegendItem()
```
### AngleAbove

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Gets or sets the angle above. Reserved for future implementation.</p>


```csharp
public double AngleAbove { get; set; }
```
### AngleBelow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Gets or sets the angle below. Reserved for future implementation.</p>


```csharp
public double AngleBelow { get; set; }
```
### Arrangement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Gets or sets the Arrangement.</p>


```csharp
public LegendItemArrangement Arrangement { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHorizontalBarLegendItem.</p>


```csharp
public CIMHorizontalBarLegendItem Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Reconstructs the CIMHorizontalBarLegendItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMHorizontalBarLegendItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Gets or sets the line length for a legend item leader.</p>


```csharp
public double LineLength { get; set; }
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Gets or sets the line symbol for a legend item leader.</p>


```csharp
public CIMSymbolReference LineSymbol { get; set; }
```
### PatchAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value that allows alignment of graduated symbols to be specified.</p>


```csharp
public VerticalAlignment PatchAlignment { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHorizontalBarLegendItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHorizontalBarLegendItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


