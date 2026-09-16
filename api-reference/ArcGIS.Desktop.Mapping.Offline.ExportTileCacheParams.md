# ExportTileCacheParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Offline.html">Offline</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.ExportTileCacheParams.yml" sourcestartlinenumber="1">Specifies the parameters for exporting raster
or vector tile caches.</p>


## Object Signature

```csharp
public class ExportTileCacheParams
```


## Members

### ExportTileCacheParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.ExportTileCacheParams.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Mapping.Offline.ExportTileCacheParams" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public ExportTileCacheParams()
```
### DestinationFolder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.ExportTileCacheParams.yml" sourcestartlinenumber="1">Gets and sets the folder into which the local tile cache(s) will be copied (optional).</p>


```csharp
public string DestinationFolder { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.ExportTileCacheParams.yml" sourcestartlinenumber="1">Gets and sets the extent of the area to be included in tile cache.</p>


```csharp
public Envelope Extent { get; set; }
```
### MaximumUserDefinedScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.ExportTileCacheParams.yml" sourcestartlinenumber="1">Gets and sets the maximum scale of data in the tile cache.</p>


```csharp
public double MaximumUserDefinedScale { get; set; }
```


