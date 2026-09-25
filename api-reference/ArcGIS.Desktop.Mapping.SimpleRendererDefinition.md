# SimpleRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SimpleRendererDefinition.yml" sourcestartlinenumber="1">Represents simple renderer definition to draw all features in a layer with a common symbol.</p>


## Object Signature

```csharp
public class SimpleRendererDefinition : RendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.SimpleRendererDefinition.yml" sourcestartlinenumber="1">Once you define a simple renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a feature layer.</p>


## Members

### SimpleRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SimpleRendererDefinition.yml" sourcestartlinenumber="1">Creates a simple renderer definition.</p>


```csharp
public SimpleRendererDefinition()
```
### SimpleRendererDefinition(CIMSymbolReference, string, string)

- Kind: constructor


```csharp
public SimpleRendererDefinition(CIMSymbolReference symbol, string label = null, string description = null)
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SimpleRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SimpleRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the label that will show up on the TOC next the symbol.</p>


```csharp
public string Label { get; set; }
```
### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SimpleRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a template for the symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```


