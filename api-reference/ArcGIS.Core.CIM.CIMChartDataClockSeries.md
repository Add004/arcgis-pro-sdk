# CIMChartDataClockSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Provides access to members that control DataClock series.</p>


## Object Signature

```csharp
public class CIMChartDataClockSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartDataClockSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Provides access to members that control DataClock series.</p>


```csharp
public CIMChartDataClockSeries()
```
### BreakColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the color for each break.</p>


```csharp
public CIMColor[] BreakColors { get; set; }
```
### Breaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the upper bound breaks.</p>


```csharp
public double[] Breaks { get; set; }
```
### BreaksCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the number of breaks for automatic breaks creation.</p>


```csharp
public int BreaksCount { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the classification method with which breaks are created.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartDataClockSeries.</p>


```csharp
public CIMChartDataClockSeries Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the color ramp from which break colors are created.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartDataClockSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartDataClockSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### MinimumBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the lower bound of the first range.</p>


```csharp
public double MinimumBreak { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets color properties for empty cells.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### NullPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the policy for handling missing data.</p>


```csharp
public ChartNullPolicy NullPolicy { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RingTimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the time units for rings.</p>


```csharp
public esriTimeUnits RingTimeUnits { get; set; }
```
### ShowWedgeLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the wedge label is visible.</p>


```csharp
public bool ShowWedgeLabel { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartDataClockSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrimIncompleteTimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether incomplete time intervals at the ends of time interval ranges are trimmed in order to avoid bias.</p>


```csharp
public bool TrimIncompleteTimeInterval { get; set; }
```
### WedgeLabelText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the text symbol properties for the wedge label.</p>


```csharp
public CIMChartTextProperties WedgeLabelText { get; set; }
```
### WedgeTimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Gets or sets the time units for wedges.</p>


```csharp
public esriTimeUnits WedgeTimeUnits { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDataClockSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


