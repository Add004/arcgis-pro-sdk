# TinUniqueValueRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Represents a unique value renderer definition to draw all objects in a surface layer.</p>


## Object Signature

```csharp
public abstract class TinUniqueValueRendererDefinition : TinRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Once you define a unique value renderer, you can call a surface layer's <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanCreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CanCreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CreateRenderer(ArcGIS.Desktop.Mapping.TinRendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.CanSetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=CanSetRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.SetRenderer(ArcGIS.Core.CIM.CIMTinRenderer%2cArcGIS.Desktop.Mapping.SurfaceRendererTarget)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a surface layer.</p>


## Members

### SymbolTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a template for the symbol used in the renderer.</p>


```csharp
public CIMSymbolReference SymbolTemplate { get; set; }
```
### UseDefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinUniqueValueRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets a boolean to indicate that the DefaultSymbol will be used to draw features.
Default value is false.</p>


```csharp
public bool UseDefaultSymbol { get; set; }
```


