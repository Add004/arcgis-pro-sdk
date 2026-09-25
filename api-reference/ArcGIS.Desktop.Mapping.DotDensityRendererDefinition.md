# DotDensityRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Represents a dot density symbol renderer definition to show quantitative values for a
field as a series of pattern fills based on the field value for each polygon.</p>


## Object Signature

```csharp
public class DotDensityRendererDefinition : RendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">With dot density symbology, the data you symbolize is not classified.
Instead, quantitative values for one or more fields are represented as a
collection of point symbols (typically solid circles or dots) within each polygon.
Each dot represents a constant number of things, or people, or other quantifiable phenomena.
The dots are equally sized, even when multiple fields are symbolized together within a layer.</p>


## Members

### DotDensityRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public DotDensityRendererDefinition()
```
### DotDensityRendererDefinition(List&lt;string&gt;, CIMColorRamp, double, double, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Create a DotDensityRendererDefinition.</p>


```csharp
public DotDensityRendererDefinition(List<string> fields, CIMColorRamp colorRamp = null, double dotSize = 2, double dotValue = 1, string symbolLabel = "", string unitLabel = "")
```
### ArcadeExpressions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the arcade expression to be used to get unique values or combination of values from.
This is required if <xref href="ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.ValueFields?text=ValueFields" data-throw-if-not-resolved="false"></xref> is null.</p>


```csharp
public List<string> ArcadeExpressions { get; set; }
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the background symbol.</p>


```csharp
public CIMSymbolReference BackgroundSymbol { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the color ramp be used to pick color for symbols from.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DotSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the dot size.</p>


```csharp
public double DotSize { get; set; }
```
### DotValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the dot value.</p>


```csharp
public double DotValue { get; set; }
```
### SymbolLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the symbol label.</p>


```csharp
public string SymbolLabel { get; set; }
```
### UnitLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the unit label.</p>


```csharp
public string UnitLabel { get; set; }
```
### ValueFields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets one or more fields to be used to get values or combination of values from.
This is required if <xref href="ArcGIS.Desktop.Mapping.DotDensityRendererDefinition.ArcadeExpressions?text=ArcadeExpressions" data-throw-if-not-resolved="false"></xref> is null.</p>


```csharp
public List<string> ValueFields { get; set; }
```


