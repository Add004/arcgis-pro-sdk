# ColormapColorizerDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Represents a colorizer definition for a Colormap colorizer to apply a color map to the values in the dataset.</p>


## Object Signature

```csharp
public class ColormapColorizerDefinition : RasterColorizerDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">ColormapColorizerDefinition class allows you to define a simplified list of parameters to create a Colormap colorizer.<br>
Once you define a Colormap colorizer definition, you can call the <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.CreateColorizer(ArcGIS.Desktop.Mapping.RasterColorizerDefinition)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.SetColorizer(ArcGIS.Core.CIM.CIMRasterColorizer)" data-throw-if-not-resolved="false"></xref>methods to create and assign a Colormap colorizer to a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### ColormapColorizerDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Creates a default Colormap colorizer definition.</p>


```csharp
public ColormapColorizerDefinition()
```
### ColormapColorizerDefinition(List&lt;CIMColor&gt;, List&lt;int&gt;, List&lt;string&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Creates a Colormap colorizer definition with parameters.</p>


```csharp
public ColormapColorizerDefinition(List<CIMColor> colors, List<int> values, List<string> labels)
```
### ColormapColorizerDefinition(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Creates a Colormap colorizer definition with the Colormap file path.</p>


```csharp
public ColormapColorizerDefinition(string colormapFilePath)
```
### ColormapFilePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the file path of a colormap file.</p>


```csharp
public string ColormapFilePath { get; set; }
```
### Colors

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the list of <xref href="ArcGIS.Core.CIM.CIMColor" data-throw-if-not-resolved="false"></xref>s.</p>


```csharp
public List<CIMColor> Colors { get; set; }
```
### Labels

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the list of color labels.</p>


```csharp
public List<string> Labels { get; set; }
```
### NoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the NoData color.</p>


```csharp
public CIMColor NoDataColor { get; set; }
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColormapColorizerDefinition.yml" sourcestartlinenumber="1">Gets and sets the list of pixel values.</p>


```csharp
public List<int> Values { get; set; }
```


