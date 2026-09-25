# UniqueValueRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Represents unique value renderer definition to apply a different symbol to each category of feature within the layer based on one or more fields.</p>


## Object Signature

```csharp
public class UniqueValueRendererDefinition : RendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">UniqueValueRendererDefinition class allows you to define parameters to create renderers to draw features based on unique values.<br>
Once you define a unique value renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a feature layer.</p>


## Members

### UniqueValueRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Creates a UniqueValueRendererDefinition.</p>


```csharp
public UniqueValueRendererDefinition()
```
### UniqueValueRendererDefinition(List&lt;string&gt;, CIMSymbolReference, CIMColorRamp, CIMSymbolReference, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Creates a UniqueValueRendererDefinition.</p>


```csharp
public UniqueValueRendererDefinition(List<string> fields, CIMSymbolReference symbolTemplate = null, CIMColorRamp colorRamp = null, CIMSymbolReference defaultSymbol = null, bool useDefaultSymbol = true)
```
### ArcadeExpression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the arcade expression to be used to get unique values or combination of values from.
This is required if <xref href="ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.ValueFields?text=ValueFields" data-throw-if-not-resolved="false"></xref> is null.</p>


```csharp
public string ArcadeExpression { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the color ramp be used to pick color for symbols from.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a symbol that will be used to draw features whose values are not found in values list.</p>


```csharp
public CIMSymbolReference DefaultSymbol { get; set; }
```
### FieldDelimiter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a string to as delimiter while concatenating values from multiple fields.</p>


```csharp
public string FieldDelimiter { get; set; }
```
### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a template for symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```
### UseDefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a boolean to indicate that DefaultSymbol will be used to draw features whose values are not found in the values list.</p>


```csharp
public bool UseDefaultSymbol { get; set; }
```
### ValueFields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets one or more fields to be used to get unique values or combination of values from.
This is required if <xref href="ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.ArcadeExpression?text=ArcadeExpression" data-throw-if-not-resolved="false"></xref> is null.</p>


```csharp
public List<string> ValueFields { get; set; }
```
### ValuesLimit

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a limit on how many unique values will be retrieved from the table.</p>


```csharp
public int ValuesLimit { get; set; }
```


