# BasicRasterLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Represents a basic raster layer.</p>


## Object Signature

```csharp
public abstract class BasicRasterLayer : Layer, IMetadataInfo, IMetadataSource
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">The basic raster layer is the basis for all raster layers.</p>


## Members

### BasicRasterLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Represents a basic raster layer.</p>


```csharp
protected BasicRasterLayer()
```
### CanCreateColorizer(RasterColorizerDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Determines whether a colorizer can be created and is valid for the raster layer using the specified <xref href="ArcGIS.Desktop.Mapping.RasterColorizerDefinition" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanCreateColorizer(RasterColorizerDefinition colorizerDefinition)
```
### CanSetColorizer(CIMRasterColorizer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Determines whether a colorizer is valid for the raster layer and can be updated.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSetColorizer(CIMRasterColorizer colorizer)
```
### CreateColorizer(RasterColorizerDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.CIM.CIMRasterColorizer" data-throw-if-not-resolved="false"></xref> specifically for a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref> using a defined <xref href="ArcGIS.Desktop.Mapping.RasterColorizerDefinition" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRasterColorizer CreateColorizer(RasterColorizerDefinition colorizerDefinition)
```
### CreateColorizerAsync(RasterColorizerDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.CIM.CIMRasterColorizer" data-throw-if-not-resolved="false"></xref> specifically for a <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref> using a defined <xref href="ArcGIS.Desktop.Mapping.RasterColorizerDefinition" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Task<CIMRasterColorizer> CreateColorizerAsync(RasterColorizerDefinition colorizerDefinition)
```
### GetApplicableColorizers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Gets a list of the <xref href="ArcGIS.Desktop.Mapping.RasterColorizerType" data-throw-if-not-resolved="false"></xref>s that can be applied to this <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public List<RasterColorizerType> GetApplicableColorizers()
```
### GetColorizer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Gets the colorizer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRasterColorizer GetColorizer()
```
### GetRaster()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Returns this basic raster layer's underlying <xref href="ArcGIS.Core.Data.Raster.Raster" data-throw-if-not-resolved="false"></xref> object.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Raster GetRaster()
```
### GetRenderingRule()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Gets the rendering rule. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRenderingRule GetRenderingRule()
```
### SelectionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Gets the number of items selected in the layer.</p>


```csharp
public int SelectionCount { get; }
```
### SetColorizer(CIMRasterColorizer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Sets the colorizer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetColorizer(CIMRasterColorizer colorizer)
```
### SetRenderingRule(CIMRenderingRule)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicRasterLayer.yml" sourcestartlinenumber="1">Sets the rendering rule. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRenderingRule(CIMRenderingRule renderingRule)
```


