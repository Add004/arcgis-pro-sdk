# ClassBreaksRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Represents an abstract class definition for class breaks renderers.</p>


## Object Signature

```csharp
public abstract class ClassBreaksRendererDefinition : RendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">ClassBreaksRendererDefinition defines the parameters for drawing features based on the values of a quantitative attribute that is statistically grouped by a classification algorithm. <br>
To set up a ClassBreaksRenderer you first need to know how many classes you will have. Then you specify a particular classification algorithm (e.g. natural breaks, quantile, equal interval)
to your data to compute class breaks for your renderer.
You also provide the color ramp.
Once you define a renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a feature layer.</p>


## Members

### ArcadeExpression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the arcade expression used in the renderer.
This is required if <xref href="ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.ClassificationField?text=ClassificationField" data-throw-if-not-resolved="false"></xref> is null.</p>


```csharp
public string ArcadeExpression { get; set; }
```
### BreakCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets number of desired class breaks. The default value is 5.</p>


```csharp
public int BreakCount { get; set; }
```
### ClassificationField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets field name used in the renderer.
This is required if <xref href="ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.ArcadeExpression?text=ArcadeExpression" data-throw-if-not-resolved="false"></xref> is null.</p>


```csharp
public string ClassificationField { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets and sets classification method to be used to compute class breaks. This is required.
The default value is <xref href="ArcGIS.Core.CIM.ClassificationMethod.NaturalBreaks" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the color ramp be used to pick color for symbols from.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DeviationInterval

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or set standard deviation interval.</p>


```csharp
public StandardDeviationInterval DeviationInterval { get; set; }
```
### ExclusionClause

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a SQL statement to exclude features while computing class breaks.</p>


```csharp
public string ExclusionClause { get; set; }
```
### ExclusionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the label used on the TOC for exclusion symbol.</p>


```csharp
public string ExclusionLabel { get; set; }
```
### ExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets symbol to be used to draw features that are excluded since they meet <xref href="ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.ExclusionClause?text=ExclusionClause" data-throw-if-not-resolved="false"></xref> criteria.</p>


```csharp
public CIMSymbolReference ExclusionSymbol { get; set; }
```
### IntervalSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the interval size.</p>


```csharp
public double IntervalSize { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the field which will be used to normalize data when 'Field' is selected as the <xref href="ArcGIS.Core.CIM.DataNormalizationMethod?text=DataNormalizationMethod" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the method be used to normalized data.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the number format used in the renderer.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### OutOfRangeDescription

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the out of range description used in the renderer.</p>


```csharp
public string OutOfRangeDescription { get; set; }
```
### OutOfRangeLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the out of range label used in the renderer.</p>


```csharp
public string OutOfRangeLabel { get; set; }
```
### OutOfRangeSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the out of range symbol used in the renderer.</p>


```csharp
public CIMSymbolReference OutOfRangeSymbol { get; set; }
```
### SampleSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets number of records be used as samples to compute class breaks.</p>


```csharp
public int SampleSize { get; set; }
```
### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a template for symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```
### UseOutOfRangeSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a boolean to indicate that OutOfRangeSymbol will be used to draw features whose values are not found in the values list.</p>


```csharp
public bool UseOutOfRangeSymbol { get; set; }
```


