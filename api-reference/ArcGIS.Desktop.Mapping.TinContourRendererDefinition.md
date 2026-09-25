# TinContourRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Represents a renderer definition to draw contours in a surface layer.</p>


## Object Signature

```csharp
public class TinContourRendererDefinition : TinRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Once you define a renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### TinContourRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Creates a contour renderer definition.</p>


```csharp
public TinContourRendererDefinition()
```
### TinContourRendererDefinition(CIMSymbolReference, string, string, CIMSymbolReference, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Creates a contour renderer definition.</p>


```csharp
public TinContourRendererDefinition(CIMSymbolReference symbolTemplate, string label, string description, CIMSymbolReference indexSymbolTemplate, string indexLabel, string indexDescription)
```
### ContourFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the contour factor.  The default value is 5.</p>


```csharp
public int ContourFactor { get; set; }
```
### ContourInterval

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the contour interval.  The default value is 5.0.</p>


```csharp
public double ContourInterval { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### IndexDescription

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the index description.</p>


```csharp
public string IndexDescription { get; set; }
```
### IndexLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the label that will show up on the TOC next to the index symbol.</p>


```csharp
public string IndexLabel { get; set; }
```
### IndexSymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a template for the index symbol used in the renderer.</p>


```csharp
public CIMSymbolReference IndexSymbolTemplate { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the label that will show up on the TOC next to the symbol.</p>


```csharp
public string Label { get; set; }
```
### ReferenceHeight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the contour reference height.  The default value is 0.0.</p>


```csharp
public double ReferenceHeight { get; set; }
```
### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinContourRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a template for the symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```


