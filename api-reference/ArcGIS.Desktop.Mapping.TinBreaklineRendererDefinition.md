# TinBreaklineRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Represents a unique value renderer definition to draw breaklines in a surface layer.</p>


## Object Signature

```csharp
public class TinBreaklineRendererDefinition : TinUniqueValueRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Once you define a unique value renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### TinBreaklineRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Creates a breakline renderer definition.</p>


```csharp
public TinBreaklineRendererDefinition()
```
### TinBreaklineRendererDefinition(CIMSymbolReference, CIMSymbolReference, CIMSymbolReference, CIMSymbolReference, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Creates a breakline renderer definition.</p>


```csharp
public TinBreaklineRendererDefinition(CIMSymbolReference regularEdgeSymbol, CIMSymbolReference hardEdgeSymbol, CIMSymbolReference softEdgeSymbol, CIMSymbolReference outsideEdgeSymbol, bool useDefaultSymbol = false)
```
### TinBreaklineRendererDefinition(CIMSymbolReference, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Creates a breakline renderer definition.</p>


```csharp
public TinBreaklineRendererDefinition(CIMSymbolReference symbolTemplate, bool useDefaultSymbol = false)
```
### HardEdgeSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a symbol used for hard edges in the renderer.</p>


```csharp
public CIMSymbolReference HardEdgeSymbol { get; set; }
```
### OutsideEdgeSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a symbol used for outside edges in the renderer.</p>


```csharp
public CIMSymbolReference OutsideEdgeSymbol { get; set; }
```
### RegularEdgeSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a symbol used for regular edges in the renderer.</p>


```csharp
public CIMSymbolReference RegularEdgeSymbol { get; set; }
```
### SoftEdgeSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinBreaklineRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a symbol used for soft edges in the renderer.</p>


```csharp
public CIMSymbolReference SoftEdgeSymbol { get; set; }
```


