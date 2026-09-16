# GenerateOfflineMap

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Offline.html">Offline</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Provides support for taking map content offline, to include:
Generating, syncing, and removing replicas for a given map's content.
Support is also included for exporting raster and vector tile caches.</p>


## Object Signature

```csharp
public class GenerateOfflineMap
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Refer to
<a href="https://pro.arcgis.com/en/pro-app/latest/help/projects/take-a-map-offline.htm">Take a map offline</a>
in the Pro documentation for the corresponding UI functionality</p>


## Members

### ExportRasterTileCache(Map, ExportTileCacheParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Export raster tile caches from the map using the specified
<xref href="ArcGIS.Desktop.Mapping.Offline.ExportTileCacheParams" data-throw-if-not-resolved="false"></xref>. This method must be called on the
MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportRasterTileCache(Map map, ExportTileCacheParams cacheParams)
```
### ExportVectorTileCache(Map, ExportTileCacheParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Export vector tile caches from the map using the specified
<xref href="ArcGIS.Desktop.Mapping.Offline.ExportTileCacheParams" data-throw-if-not-resolved="false"></xref>. This method must be called on the
MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportVectorTileCache(Map map, ExportTileCacheParams cacheParams)
```
### GenerateReplicas(Map, GenerateReplicaParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Generate bi-directional replicas for all sync-enabled content
in the map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void GenerateReplicas(Map map, GenerateReplicaParams replicaParams)
```
### GetCanExportRasterTileCache(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Gets whether the map contains one or more raster tile caches
that can be exported. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public bool GetCanExportRasterTileCache(Map map)
```
### GetCanExportVectorTileCache(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Gets whether the map contains one or more vector tile caches
that can be exported. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public bool GetCanExportVectorTileCache(Map map)
```
### GetCanGenerateReplicas(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Gets whether the map contains sync-enabled content.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetCanGenerateReplicas(Map map)
```
### GetCanRemoveReplicas(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Gets whether the map contains <b><i>local</i></b> syncable content that can
be unregistered with the feature service. This method must be called on the
MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetCanRemoveReplicas(Map map)
```
### GetCanSynchronizeReplicas(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Gets whether the map contains <b><i>local</i></b> syncable content that can
be sync'd with its feature service. This method must be called on the
MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetCanSynchronizeReplicas(Map map)
```
### GetExportRasterTileCacheScales(Map, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Get the list of scales to use for determining the level of detail, LOD,
to use when exporting a raster tile cache. This method must be called on
the MCT. Use QueuedTask.Run.</p>


```csharp
public List<double> GetExportRasterTileCacheScales(Map map, Envelope extent)
```
### GetExportVectorTileCacheScales(Map, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Get the list of scales to use for determining the level of detail, LOD,
to use when exporting a vector tile cache. This method must be called on
the MCT. Use QueuedTask.Run.</p>


```csharp
public List<double> GetExportVectorTileCacheScales(Map map, Envelope extent)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">The singleton instance of GenerateOfflineMap.</p>


```csharp
public static GenerateOfflineMap Instance { get; }
```
### RemoveReplicas(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Removes all replicas from the map content.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveReplicas(Map map)
```
### SynchronizeReplicas(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateOfflineMap.yml" sourcestartlinenumber="1">Performs a bi-directional sync between all replica content
in the map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SynchronizeReplicas(Map map)
```


