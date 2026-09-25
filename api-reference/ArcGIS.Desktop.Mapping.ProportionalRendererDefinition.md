# ProportionalRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Represents a proportional renderer definition to draw features proportionally to each other.</p>


## Object Signature

```csharp
public class ProportionalRendererDefinition : RendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Once you define a proportional renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a feature layer.</p>


## Members

### ProportionalRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Creates a ProportionalRendererDefinition.</p>


```csharp
public ProportionalRendererDefinition()
```
### ProportionalRendererDefinition(string, CIMSymbolReference, double, double?, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Creates a ProportionalRendererDefinition.</p>


```csharp
public ProportionalRendererDefinition(string field, CIMSymbolReference symbolTemplate, double minimumSymbolSize = 4, double? maximumSymbolSize = null, bool isMaximumSymbolSizeCapped = true)
```
### ProportionalRendererDefinition(string, esriUnits, CIMSymbolReference, SymbolShapes, ValueRepresentations)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Creates a ProportionalRendererDefinition.</p>


```csharp
public ProportionalRendererDefinition(string field, esriUnits units, CIMSymbolReference symbolFill, SymbolShapes proportionalSymbolType = 1, ValueRepresentations valueRepresentations = 0)
```
### ProportionalRendererDefinition(string, esriUnits, SymbolShapes, ValueRepresentations)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Creates a ProportionalRendererDefinition.</p>


```csharp
public ProportionalRendererDefinition(string field, esriUnits units, SymbolShapes proportionalSymbolType = 1, ValueRepresentations valueRepresentations = 0)
```
### ProportionalRendererDefinition(string, double, double?, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Creates a ProportionalRendererDefinition.</p>


```csharp
public ProportionalRendererDefinition(string field, double minimumSymbolSize = 4, double? maximumSymbolSize = null, bool isMaximumSymbolSizeCapped = true)
```
### ArcadeExpression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the arcade expression used in the renderer.</p>


```csharp
public string ArcadeExpression { get; set; }
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the background symbol used in the renderer.</p>


```csharp
public CIMPolygonSymbol BackgroundSymbol { get; set; }
```
### ExclusionClause

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a SQL statement to exclude features while computing class breaks.</p>


```csharp
public string ExclusionClause { get; set; }
```
### ExclusionDescription

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the exclusion description used in the renderer.</p>


```csharp
public string ExclusionDescription { get; set; }
```
### ExclusionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the exclusion label used in the renderer.</p>


```csharp
public string ExclusionLabel { get; set; }
```
### ExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the exclusion symbol used in the renderer.</p>


```csharp
public CIMSymbolReference ExclusionSymbol { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the field used in the renderer.</p>


```csharp
public string Field { get; set; }
```
### FlanneryCompensation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the flannery compensation used in the renderer.</p>


```csharp
public bool FlanneryCompensation { get; set; }
```
### IsMaximumSymbolSizeCapped

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets whether the maximum symbol size is capped.</p>


```csharp
public bool IsMaximumSymbolSizeCapped { get; set; }
```
### LegendSymbolCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the legend symbol count used in the renderer.</p>


```csharp
public int LegendSymbolCount { get; set; }
```
### LowerSizeStop

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets lower size stop on the histogram.</p>


```csharp
public double? LowerSizeStop { get; set; }
```
### MaximumSymbolSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the maximum symbol size used in the renderer.</p>


```csharp
public double? MaximumSymbolSize { get; set; }
```
### MinimumSymbolSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the minimum symbol size used in the renderer.</p>


```csharp
public double MinimumSymbolSize { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the normalization field used in the renderer.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the normalization type used in the renderer.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### NullValueDescription

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the out of range description used in the renderer.</p>


```csharp
public string NullValueDescription { get; set; }
```
### NullValueLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the out of range label used in the renderer.</p>


```csharp
public string NullValueLabel { get; set; }
```
### NullValueSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the symbol used in the renderer to draw features with null values.</p>


```csharp
public CIMSymbolReference NullValueSymbol { get; set; }
```
### ProportionalSymbolType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the proportional symbol type used in the renderer.</p>


```csharp
public SymbolShapes ProportionalSymbolType { get; set; }
```
### ShowNullValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets whether null values are shown in the renderer.</p>


```csharp
public bool ShowNullValues { get; set; }
```
### SymbolFill

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the symbol fill used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolFill { get; set; }
```
### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the template for the symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```
### Units

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the units used in the renderer.</p>


```csharp
public esriUnits Units { get; set; }
```
### UpperSizeStop

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets upper size stop on the histogram.</p>


```csharp
public double? UpperSizeStop { get; set; }
```
### ValueRepresentations

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ProportionalRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the value representation used in the renderer.</p>


```csharp
public ValueRepresentations ValueRepresentations { get; set; }
```


