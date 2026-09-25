# CIMChartDimensionalProfileDimensionValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Represents a dimension value for a given variable to be plotted over time.</p>


## Object Signature

```csharp
public class CIMChartDimensionalProfileDimensionValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartDimensionalProfileDimensionValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Represents a dimension value for a given variable to be plotted over time.</p>


```csharp
public CIMChartDimensionalProfileDimensionValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartDimensionalProfileDimensionValue.</p>


```csharp
public CIMChartDimensionalProfileDimensionValue Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Reconstructs the CIMChartDimensionalProfileDimensionValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartDimensionalProfileDimensionValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### LocationID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the index of the location this definition corresponds to.</p>


```csharp
public int LocationID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartDimensionalProfileDimensionValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Gets or sets the value.</p>


```csharp
public double Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileDimensionValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


