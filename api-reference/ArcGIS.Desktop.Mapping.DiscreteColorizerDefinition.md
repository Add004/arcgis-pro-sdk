# DiscreteColorizerDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiscreteColorizerDefinition.yml" sourcestartlinenumber="1">Represents a colorizer definition for a Discrete colorizer that enables you to display your dataset using a specific number of colors, each color represents the same number of values.</p>


## Object Signature

```csharp
public class DiscreteColorizerDefinition : RasterColorizerDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiscreteColorizerDefinition.yml" sourcestartlinenumber="1">DiscreteColorizerDefinition class allows you to define a simplified list of parameters to create a Discrete colorizer.<br>
Once you define a Discrete colorizer definition, you can call the <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.CreateColorizer(ArcGIS.Desktop.Mapping.RasterColorizerDefinition)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.SetColorizer(ArcGIS.Core.CIM.CIMRasterColorizer)" data-throw-if-not-resolved="false"></xref> methods to create and assign a Discrete colorizer to a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### DiscreteColorizerDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiscreteColorizerDefinition.yml" sourcestartlinenumber="1">Creates a default Discrete colorizer definition.</p>


```csharp
public DiscreteColorizerDefinition()
```
### DiscreteColorizerDefinition(int, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiscreteColorizerDefinition.yml" sourcestartlinenumber="1">Creates a Discrete colorizer definition with parameters.</p>


```csharp
public DiscreteColorizerDefinition(int numberOfColors, CIMColorRamp colorRamp = null)
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiscreteColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiscreteColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the NoData color.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### NumberOfColors

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiscreteColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the number of colors.</p>


```csharp
public int? NumberOfColors { get; set; }
```


