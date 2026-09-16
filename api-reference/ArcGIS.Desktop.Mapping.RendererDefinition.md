# RendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.RendererDefinition.yml" sourcestartlinenumber="1">Represents an abstract class definition for all types of renderers.</p>


## Object Signature

```csharp
public abstract class RendererDefinition : LayerDrawingDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.RendererDefinition.yml" sourcestartlinenumber="1">RendererDefinition classes allow you to define parameters to create renderers to draw features with simple renderer or based on unique values
or the values of a quantitative attribute that is statistically grouped by a classification algorithm.<br>
Once you define a renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a feature layer.</p>





