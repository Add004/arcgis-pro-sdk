# TGAFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TGAFormat.yml" sourcestartlinenumber="1">Represents a Truevision Graphics Adaptor (TGA) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class TGAFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TGAFormat.yml" sourcestartlinenumber="1">TGA files have historically been used for content that is meant to be used in other applications (for example, image sprites for animated games)
and is read and written by many popular graphic arts applications.</p>


## Members

### TGAFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TGAFormat.yml" sourcestartlinenumber="1">Initialize a new instance of TGAFormat.</p>


```csharp
public TGAFormat()
```
### ColorMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TGAFormat.yml" sourcestartlinenumber="1">Gets or sets the number of bits used to describe color.</p>


```csharp
public TGAColorMode ColorMode { get; set; }
```
### GeoReferenceMapFrameName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TGAFormat.yml" sourcestartlinenumber="1">Gets or sets the name of the map frame used to define the coordinate system for georeference information</p>


```csharp
public string GeoReferenceMapFrameName { get; set; }
```
### HasTransparentBackground

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TGAFormat.yml" sourcestartlinenumber="1">Gets or sets if the background will be transparent.</p>


```csharp
public bool HasTransparentBackground { get; set; }
```
### HasWorldFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TGAFormat.yml" sourcestartlinenumber="1">Gets or sets if a georeferenced world file will be created.</p>


```csharp
public bool HasWorldFile { get; set; }
```


