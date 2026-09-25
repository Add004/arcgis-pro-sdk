# StackedChartRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StackedChartRendererDefinition.yml" sourcestartlinenumber="1">Represents a stacked chart renderer definition to display amounts by category. Each feature
is annotated with a chart that shows the amounts present in each category.</p>


## Object Signature

```csharp
public class StackedChartRendererDefinition : ChartRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.StackedChartRendererDefinition.yml" sourcestartlinenumber="1">Default orientation is vertical or &quot;column&quot;</p>


## Members

### StackedChartRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StackedChartRendererDefinition.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Mapping.StackedChartRendererDefinition" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public StackedChartRendererDefinition()
```
### Orientation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StackedChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets the chart orientation.</p>


```csharp
public ChartOrientation Orientation { get; set; }
```
### ShowOutline

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StackedChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets whether to show an outline</p>


```csharp
public bool ShowOutline { get; set; }
```
### SizeOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StackedChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets the stack chart size option</p>


```csharp
public StackChartSizeOptions SizeOption { get; set; }
```
### StackLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StackedChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets the length of the stack chart in pts</p>


```csharp
public double StackLength { get; set; }
```
### StackWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StackedChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets the width of the stack chart in pts</p>


```csharp
public double StackWidth { get; set; }
```


