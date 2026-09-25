# UniqueValueColorizerDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueColorizerDefinition.yml" sourcestartlinenumber="1">Represents a colorizer definition for a Unique Value colorizer that randomly assigns a color for each value in the dataset.</p>


## Object Signature

```csharp
public class UniqueValueColorizerDefinition : RasterColorizerDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueColorizerDefinition.yml" sourcestartlinenumber="1">UVColorizerDefinition class allows you to define a simplified list of parameters to create a Unique Value colorizer.<br>
Once you define a Unique Value colorizer definition, you can call the <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.CreateColorizer(ArcGIS.Desktop.Mapping.RasterColorizerDefinition)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.SetColorizer(ArcGIS.Core.CIM.CIMRasterColorizer)" data-throw-if-not-resolved="false"></xref> methods to create and assign a Unique Value colorizer to a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### UniqueValueColorizerDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueColorizerDefinition.yml" sourcestartlinenumber="1">Creates a default Unique Value colorizer definition.</p>


```csharp
public UniqueValueColorizerDefinition()
```
### UniqueValueColorizerDefinition(string, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueColorizerDefinition.yml" sourcestartlinenumber="1">Creates a Unique Value colorizer definition using parameters.</p>


```csharp
public UniqueValueColorizerDefinition(string fieldName, CIMColorRamp colorRamp = null)
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the field name to render.</p>


```csharp
public string FieldName { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UniqueValueColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the NoData color.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```


