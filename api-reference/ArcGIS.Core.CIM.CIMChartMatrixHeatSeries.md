# CIMChartMatrixHeatSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Provides access to members that control MatrixHeat series.</p>


## Object Signature

```csharp
public class CIMChartMatrixHeatSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartMatrixHeatSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Provides access to members that control MatrixHeat series.</p>


```csharp
public CIMChartMatrixHeatSeries()
```
### BreakColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the color for each break.</p>


```csharp
public CIMColor[] BreakColors { get; set; }
```
### Breaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the upper bound breaks.</p>


```csharp
public double[] Breaks { get; set; }
```
### BreaksCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the number of breaks for automatic breaks creation.</p>


```csharp
public int BreaksCount { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the classification method with which breaks are created.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartMatrixHeatSeries.</p>


```csharp
public CIMChartMatrixHeatSeries Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the color ramp from which break colors are created.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### ColumnSortedCategoryValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the array of sorted category values for column-wise custom sort.</p>


```csharp
public string[] ColumnSortedCategoryValues { get; set; }
```
### ColumnsTimeBinningProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the time binning properties for column category field values.
If null, matrix heat series will use unique values to create column categories.</p>


```csharp
public CIMChartTimeBinningProperties ColumnsTimeBinningProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartMatrixHeatSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartMatrixHeatSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### MinimumBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the lower bound of the first range.</p>


```csharp
public double MinimumBreak { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets color properties for empty cells.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### NullPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the policy for handling missing data.</p>


```csharp
public ChartNullPolicy NullPolicy { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RowSortedCategoryValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the array of sorted category values for row-wise custom sort.</p>


```csharp
public string[] RowSortedCategoryValues { get; set; }
```
### RowsTimeBinningProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the time binning properties for row category field values.
If null, matrix heat series will use unique values to create row categories.</p>


```csharp
public CIMChartTimeBinningProperties RowsTimeBinningProperties { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartMatrixHeatSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMatrixHeatSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


