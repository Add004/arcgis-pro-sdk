# CIMChartDimensionalProfileBand

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Represents a band for a variable to be plotted over time.</p>


## Object Signature

```csharp
public class CIMChartDimensionalProfileBand : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartDimensionalProfileBand()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Represents a band for a variable to be plotted over time.</p>


```csharp
public CIMChartDimensionalProfileBand()
```
### BandID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Gets or sets the band ID.</p>


```csharp
public int BandID { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartDimensionalProfileBand.</p>


```csharp
public CIMChartDimensionalProfileBand Clone()
```
### Dimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Gets or sets the dimension to be plotted on the y axis.</p>


```csharp
public string Dimension { get; set; }
```
### DimensionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Gets or sets the dimension values corresponding to the dimension to be plotted on the y axis.</p>


```csharp
public double[] DimensionValues { get; set; }
```
### DimensionValuesLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Gets or sets the labels for dimension values.</p>


```csharp
public string[] DimensionValuesLabels { get; set; }
```
### DimensionValuesSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Gets or sets the symbols for dimension values.</p>


```csharp
public CIMSymbolReference[] DimensionValuesSymbols { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Reconstructs the CIMChartDimensionalProfileBand with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartDimensionalProfileBand FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### LocationID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Gets or sets the index of the location this definition corresponds to.</p>


```csharp
public int LocationID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartDimensionalProfileBand and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileBand.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


