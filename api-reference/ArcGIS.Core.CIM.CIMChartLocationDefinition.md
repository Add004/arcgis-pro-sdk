# CIMChartLocationDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Represents the definition of a location for which data is to be plotted.</p>


## Object Signature

```csharp
public class CIMChartLocationDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartLocationDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Represents the definition of a location for which data is to be plotted.</p>


```csharp
public CIMChartLocationDefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartLocationDefinition.</p>


```csharp
public CIMChartLocationDefinition Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this location is enabled or not.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMChartLocationDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartLocationDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Gets or sets the geometry.</p>


```csharp
public Geometry Geometry { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### MapLocationSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Gets or sets the symbol of this location as symbolized in the map.</p>


```csharp
public CIMSymbolReference MapLocationSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Gets or sets the symbol of this location as symbolized in the chart.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartLocationDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLocationDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


