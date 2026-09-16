# GraduatedSymbolsRendererDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedSymbolsRendererDefinition.yml" sourcestartlinenumber="1">Represents graduated symbol renderer definition to show qualitative differences in feature values with varying symbol sizes.</p>


## Object Signature

```csharp
public class GraduatedSymbolsRendererDefinition : ClassBreaksRendererDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedSymbolsRendererDefinition.yml" sourcestartlinenumber="1">GraduatedSymbolsRendererDefinition class allow you to define parameters to create renderers to draw features with symbols with graduated size determined based on the values of a quantitative
attribute that is statistically grouped by a classification algorithm.<br>
Once you define a graduated symbol renderer, you can call a FeatureLayer's <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)?text=CreateRenderer" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.SetRenderer(ArcGIS.Core.CIM.CIMRenderer)?text=SetRenderer" data-throw-if-not-resolved="false"></xref> methods to create and assign a renderer to a feature layer.</p>


## Members

### GraduatedSymbolsRendererDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedSymbolsRendererDefinition.yml" sourcestartlinenumber="1">Create an instance for GraduatedSymbolsRendererDefinition.</p>


```csharp
public GraduatedSymbolsRendererDefinition()
```
### GraduatedSymbolsRendererDefinition(string, ClassificationMethod, int, CIMColorRamp, CIMSymbolReference, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedSymbolsRendererDefinition.yml" sourcestartlinenumber="1">Create an instance for GraduatedSymbolsRendererDefinition.</p>


```csharp
public GraduatedSymbolsRendererDefinition(string classificationField, ClassificationMethod classificationMethod = 4, int breakCount = 5, CIMColorRamp colorRamp = null, CIMSymbolReference symbolTemplate = null, double minimumSize = 4, double maximumSize = 18)
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedSymbolsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the background symbol for polygon features.</p>


```csharp
public CIMSymbolReference BackgroundSymbol { get; set; }
```
### MaximumSymbolSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedSymbolsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the maximum symbol size.  The default value is 18.0.</p>


```csharp
public double MaximumSymbolSize { get; set; }
```
### MinimumSymbolSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraduatedSymbolsRendererDefinition.yml" sourcestartlinenumber="1">Gets or sets the minimum symbol size. The default value is 4.0.</p>


```csharp
public double MinimumSymbolSize { get; set; }
```


