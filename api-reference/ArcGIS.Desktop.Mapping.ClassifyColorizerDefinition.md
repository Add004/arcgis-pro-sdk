# ClassifyColorizerDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Represents a colorizer definition for a Classify colorizer that enables you to group pixels together in a specified number of classes.</p>


## Object Signature

```csharp
public class ClassifyColorizerDefinition : RasterColorizerDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">ClassifyColorizerDefinition class allows you to define a simplified list of parameters to create a Classify colorizer.<br>
Once you define a Classify colorizer definition, you can call the <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.CreateColorizer(ArcGIS.Desktop.Mapping.RasterColorizerDefinition)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.SetColorizer(ArcGIS.Core.CIM.CIMRasterColorizer)" data-throw-if-not-resolved="false"></xref> methods to create and assign a Classify colorizer to a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### ClassifyColorizerDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Creates a default Classify colorizer definition.</p>


```csharp
public ClassifyColorizerDefinition()
```
### ClassifyColorizerDefinition(string, int, ClassificationMethod, CIMColorRamp)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Creates a Classify colorizer definition with parameters.</p>


```csharp
public ClassifyColorizerDefinition(string fieldName, int numberOfClasses = 5, ClassificationMethod classificationType = 4, CIMColorRamp colorRamp = null)
```
### ClassificationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Core.CIM.ClassificationMethod" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ClassificationMethod? ClassificationType { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the field name to render.</p>


```csharp
public string FieldName { get; set; }
```
### IntervalSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the interval size. Use this property if <xref href="ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.ClassificationType" data-throw-if-not-resolved="false"></xref> is set to <xref href="ArcGIS.Core.CIM.ClassificationMethod.DefinedInterval" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double? IntervalSize { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the NoData color.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the field name to be used for normalization. Use this property if <xref href="ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.NormalizationType" data-throw-if-not-resolved="false"></xref> is set to <xref href="ArcGIS.Core.CIM.DataNormalizationMethod.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Core.CIM.DataNormalizationMethod" data-throw-if-not-resolved="false"></xref> to normalize the data.</p>


```csharp
public DataNormalizationMethod? NormalizationType { get; set; }
```
### NumberOfClasses

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassifyColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the number of classes.</p>


```csharp
public int? NumberOfClasses { get; set; }
```


