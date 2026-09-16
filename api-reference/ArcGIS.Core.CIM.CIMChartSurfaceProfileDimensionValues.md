# CIMChartSurfaceProfileDimensionValues

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Represents dimension values for a given variable to be plotted over a line.</p>


## Object Signature

```csharp
public class CIMChartSurfaceProfileDimensionValues : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartSurfaceProfileDimensionValues()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Represents dimension values for a given variable to be plotted over a line.</p>


```csharp
public CIMChartSurfaceProfileDimensionValues()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartSurfaceProfileDimensionValues.</p>


```csharp
public CIMChartSurfaceProfileDimensionValues Clone()
```
### Dimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Gets or sets the name of the dimension for which the values are to be plotted.</p>


```csharp
public string Dimension { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Reconstructs the CIMChartSurfaceProfileDimensionValues with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartSurfaceProfileDimensionValues FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartSurfaceProfileDimensionValues and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Gets or sets dimension values for a variable for which the values are to be plotted.</p>


```csharp
public CIMChartSurfaceProfileDimensionValue[] Values { get; set; }
```
### Variable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Gets or sets the name of the variable for which the values are to be plotted.</p>


```csharp
public string Variable { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileDimensionValues.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


