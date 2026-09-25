# GraduatedColorsRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedColorsRendererDefinition.yml" sourcestartlinenumber="1">Represents graduated color renderer definition to show qualitative differences in feature values with a range of color.</p>


## Object Signature

```csharp
public class GraduatedColorsRendererDefinition : ClassBreaksRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedColorsRendererDefinition.yml" sourcestartlinenumber="1">GraduatedColorsRendererDefinition class allow you to define parameters to create renderers to draw features with graduated color based on the values of a quantitative
attribute that is statistically grouped by a classification algorithm.<br>
Once you define a graduated color renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a feature layer.</p>


## Members

### GraduatedColorsRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedColorsRendererDefinition.yml" sourcestartlinenumber="1">Create a GraduateColorRendererDefinition.</p>


```csharp
public GraduatedColorsRendererDefinition()
```
### GraduatedColorsRendererDefinition(string, ClassificationMethod, int, CIMColorRamp, CIMSymbolReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedColorsRendererDefinition.yml" sourcestartlinenumber="1">Create a GraduateColorRendererDefinition.</p>


```csharp
public GraduatedColorsRendererDefinition(string classificationField, ClassificationMethod classificationMethod = 4, int breakCount = 5, CIMColorRamp colorRamp = null, CIMSymbolReference symbolTemplate = null)
```


