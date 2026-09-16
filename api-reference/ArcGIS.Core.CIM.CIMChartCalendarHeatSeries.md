# CIMChartCalendarHeatSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Provides access to members that control CalendarHeat series.</p>


## Object Signature

```csharp
public class CIMChartCalendarHeatSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartCalendarHeatSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Provides access to members that control CalendarHeat series.</p>


```csharp
public CIMChartCalendarHeatSeries()
```
### AggregateCalendarView

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the calendar heat chart view should be de-aggregated into consecutive calendars or aggregated into a single calendar.</p>


```csharp
public bool AggregateCalendarView { get; set; }
```
### BreakColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the color for each break.</p>


```csharp
public CIMColor[] BreakColors { get; set; }
```
### Breaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the upper bound breaks.</p>


```csharp
public double[] Breaks { get; set; }
```
### BreaksCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the number of breaks for automatic breaks creation.</p>


```csharp
public int BreaksCount { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the classification method with which breaks are created.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartCalendarHeatSeries.</p>


```csharp
public CIMChartCalendarHeatSeries Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the color ramp from which break colors are created.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### ColumnTimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the time units for columns.</p>


```csharp
public esriTimeUnits ColumnTimeUnits { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartCalendarHeatSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartCalendarHeatSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### IncludeLeapDay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a leap day (February 29) cell is a part of a chart.</p>


```csharp
public bool IncludeLeapDay { get; set; }
```
### MinimumBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the lower bound of the first range.</p>


```csharp
public double MinimumBreak { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets color properties for empty cells.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### NullPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the policy for handling missing data.</p>


```csharp
public ChartNullPolicy NullPolicy { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RowTimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Gets or sets the time units for rows.</p>


```csharp
public esriTimeUnits RowTimeUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartCalendarHeatSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartCalendarHeatSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


