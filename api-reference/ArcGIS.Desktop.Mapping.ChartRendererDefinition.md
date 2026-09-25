# ChartRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ChartRendererDefinition.yml" sourcestartlinenumber="1">Abstract base class for the different chart renderer definitions.</p>


## Object Signature

```csharp
public abstract class ChartRendererDefinition : RendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ChartRendererDefinition.yml" sourcestartlinenumber="1">Chart symbology is most effective when mapping no more
than 30 features in a 2D map. When you have more than 30 features,
patterns on the map become difficult to determine.</p>


## Members

### ChartRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ChartRendererDefinition.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public ChartRendererDefinition()
```
### ChartFields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ChartRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets one or more fields be used to create the part of the charts. This is required.</p>


```csharp
public List<string> ChartFields { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ChartRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the color ramp be used to pick color for the charts from.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DisplayIn3D

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ChartRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets whether to display the chart in 3D mode</p>


```csharp
public bool DisplayIn3D { get; set; }
```


