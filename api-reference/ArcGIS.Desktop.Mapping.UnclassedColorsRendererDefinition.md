# UnclassedColorsRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Represents an unclassed colors renderer definition to show qualitative differences in feature values with an evenly distributed color scheme.</p>


## Object Signature

```csharp
public class UnclassedColorsRendererDefinition : RendererDefinition
```

## Remarks

<p>Unclassed colors symbology is similar to graduated colors in that it's used to make choropleth maps.</p>
<p>Once you define an unclassed renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref> 
    and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a feature layer.</p>


## Members

### UnclassedColorsRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Create a UnclassedColorsRendererDefinition.</p>


```csharp
public UnclassedColorsRendererDefinition()
```
### UnclassedColorsRendererDefinition(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Create a UnclassedColorsRendererDefinition.</p>


```csharp
public UnclassedColorsRendererDefinition(string field)
```
### UnclassedColorsRendererDefinition(string, CIMSymbolReference, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Create a UnclassedColorsRendererDefinition.</p>


```csharp
public UnclassedColorsRendererDefinition(string field, CIMSymbolReference symbolTemplate, CIMColorRamp colorRamp)
```
### UnclassedColorsRendererDefinition(string, CIMSymbolReference, CIMColorRamp, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Create a UnclassedColorsRendererDefinition.</p>


```csharp
public UnclassedColorsRendererDefinition(string field, CIMSymbolReference symbolTemplate, CIMColorRamp colorRamp, string upperLabel, string lowerLabel)
```
### UnclassedColorsRendererDefinition(string, CIMSymbolReference, CIMColorRamp, string, string, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Create a UnclassedColorsRendererDefinition.</p>


```csharp
public UnclassedColorsRendererDefinition(string field, CIMSymbolReference symbolTemplate, CIMColorRamp colorRamp, string upperLabel, string lowerLabel, double upperColorStop, double lowerColorStop)
```
### ArcadeExpression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the arcade expression used in the renderer.</p>


```csharp
public string ArcadeExpression { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the colorramp for the renderer.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the field to be used in the renderer.</p>


```csharp
public string Field { get; set; }
```
### LowerColorStop

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the lower color stop for the histogram used in the renderer.</p>


```csharp
public double? LowerColorStop { get; set; }
```
### LowerLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the lower label used in the renderer.</p>


```csharp
public string LowerLabel { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the normalization field used in the renderer.</p>


```csharp
public string NormalizationField { get; set; }
```
### NullValueDescription

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the out of range description used in the renderer.</p>


```csharp
public string NullValueDescription { get; set; }
```
### NullValueLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the out of range label used in the renderer.</p>


```csharp
public string NullValueLabel { get; set; }
```
### NullValueSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the out of range symbol used in the renderer.</p>


```csharp
public CIMSymbolReference NullValueSymbol { get; set; }
```
### ShowNullValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets whether null values are shown in the renderer.</p>


```csharp
public bool ShowNullValues { get; set; }
```
### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the template for the symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```
### UpperColorStop

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the upper color stop for the histogram used in the renderer.</p>


```csharp
public double? UpperColorStop { get; set; }
```
### UpperLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UnclassedColorsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the upper label used in the renderer.</p>


```csharp
public string UpperLabel { get; set; }
```


