# CIMChartSurfaceProfileDimensionValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Represents a dimension value for a given variable to be plotted over a line.</p>


## Object Signature

```csharp
public class CIMChartSurfaceProfileDimensionValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartSurfaceProfileDimensionValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Represents a dimension value for a given variable to be plotted over a line.</p>


```csharp
public CIMChartSurfaceProfileDimensionValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartSurfaceProfileDimensionValue.</p>


```csharp
public CIMChartSurfaceProfileDimensionValue Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Reconstructs the CIMChartSurfaceProfileDimensionValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartSurfaceProfileDimensionValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### Time

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the time at which the dimension value is to be used for the profile.</p>


```csharp
public TimeInstant Time { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartSurfaceProfileDimensionValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the value.</p>


```csharp
public double Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


