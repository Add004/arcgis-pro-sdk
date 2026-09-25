# ImageMosaicSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageMosaicSubLayer.yml" sourcestartlinenumber="1">Represents the image sub-layer of a mosaic layer.</p>


## Object Signature

```csharp
public sealed class ImageMosaicSubLayer : ImageServiceLayer, IMetadataInfo, IMetadataSource, ITableDefinitionQueries
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageMosaicSubLayer.yml" sourcestartlinenumber="1">This class can be used to distinguish raster layers which are sub-layers of a mosaic layer from other types of raster layers.</p>


## Members

### SupportsSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageMosaicSubLayer.yml" sourcestartlinenumber="1">Gets whether the layer supports selection.  This always returns false for an <xref href="ArcGIS.Desktop.Mapping.ImageMosaicSubLayer" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override bool SupportsSelection { get; }
```


