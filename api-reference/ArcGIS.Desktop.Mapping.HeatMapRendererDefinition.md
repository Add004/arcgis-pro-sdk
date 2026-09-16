# HeatMapRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Represents a heat map renderer definition to draw point features as a density surface.</p>


## Object Signature

```csharp
public class HeatMapRendererDefinition : RendererDefinition
```

## Remarks

<p>Once you define a heat map renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref> 
    and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a <b>point</b> feature layer.</p>
<p>Only applicable for point feature layers.</p>


## Members

### HeatMapRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Creates a HeatMapRendererDefinition.</p>


```csharp
public HeatMapRendererDefinition()
```
### HeatMapRendererDefinition(CIMColorRamp, double, int, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Create a HeatMapRendererDefinition.</p>


```csharp
public HeatMapRendererDefinition(CIMColorRamp colorRamp, double searchRadius = 25, int renderingQuality = 5, string upperLabel = "Dense", string lowerLabel = "Sparse")
```
### HeatMapRendererDefinition(CIMColorRamp, int, int, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Create a HeatMapRendererDefinition.</p>


```csharp
public HeatMapRendererDefinition(CIMColorRamp colorRamp, int radius = 25, int renderingQuality = 5, string upperLabel = "Dense", string lowerLabel = "Sparse")
```
### HeatMapRendererDefinition(CIMColorRamp, string, double, int, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Create a HeatMapRendererDefinition.</p>


```csharp
public HeatMapRendererDefinition(CIMColorRamp colorRamp, string weightField, double searchRadius = 25, int renderingQuality = 5, string upperLabel = "Dense", string lowerLabel = "Sparse")
```
### HeatMapRendererDefinition(CIMColorRamp, string, int, int, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Create a HeatMapRendererDefinition.</p>


```csharp
public HeatMapRendererDefinition(CIMColorRamp colorRamp, string weightField, int radius = 25, int renderingQuality = 5, string upperLabel = "Dense", string lowerLabel = "Sparse")
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the color ramp be used to for the heat map.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### LowerLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets lower label that will show up on the TOC next the symbol.</p>


```csharp
public string LowerLabel { get; set; }
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Deprecated at 3.8. Use <xref href="ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.SearchRadius" data-throw-if-not-resolved="false"></xref> instead.
Gets or sets the radius used for the heat map. Default value is 25.</p>


```csharp
[Obsolete("Radius is deprecated at 3.8. Use SearchRadius instead.")]
public int Radius { get; set; }
```
### RendereringQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the renderering quality used for the heat map. Default value is 5.</p>


```csharp
public int RendereringQuality { get; set; }
```
### SearchRadius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the radius used for the heat map. Default value is 25.
This value is stored in points and supports fractional values.</p>


```csharp
public double SearchRadius { get; set; }
```
### UpperLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets upper label that will show up on the TOC next the symbol.</p>


```csharp
public string UpperLabel { get; set; }
```
### WeightField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.HeatMapRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the weight field used for the heat map.</p>


```csharp
public string WeightField { get; set; }
```


