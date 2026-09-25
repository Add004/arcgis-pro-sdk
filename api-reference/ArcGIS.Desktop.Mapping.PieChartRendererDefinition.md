# PieChartRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PieChartRendererDefinition.yml" sourcestartlinenumber="1">Represents a pie chart renderer definition to show indivudal amounts by category by their
relative proportion (to the total of all amounts).</p>


## Object Signature

```csharp
public class PieChartRendererDefinition : ChartRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.PieChartRendererDefinition.yml" sourcestartlinenumber="1">Pie charts are most effective when there are only a few categories</p>


## Members

### PieChartRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PieChartRendererDefinition.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Mapping.PieChartRendererDefinition" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PieChartRendererDefinition()
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PieChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets the field name to use in determining the overall size of the pie chart
(per feature)</p>


```csharp
public string FieldName { get; set; }
```
### FixedSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PieChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets the fixed size in points (pt).</p>


```csharp
public double FixedSize { get; set; }
```
### Orientation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PieChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets the Orientation of the pies</p>


```csharp
public PieChartOrientation Orientation { get; set; }
```
### ShowOutline

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PieChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets whether to show an outline</p>


```csharp
public bool ShowOutline { get; set; }
```
### SizeOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PieChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets the pie chart size option</p>


```csharp
public PieChartSizeOptions SizeOption { get; set; }
```


