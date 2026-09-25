# MapControlContentFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Creates content for the MapControl.</p>


## Object Signature

```csharp
public static class MapControlContentFactory
```


## Members

### Create(Map, Envelope, MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Map content for the MapControl.</p>


```csharp
public static MapControlContent Create(Map map, Envelope initialExtent, MapViewingMode viewingMode)
```
### Create(Map, Camera, MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Map content for the MapControl.</p>


```csharp
public static MapControlContent Create(Map map, Camera initialCamera, MapViewingMode viewingMode)
```
### Create(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Map content for the MapControl.</p>


```csharp
public static MapControlContent Create(MapView mapView)
```
### Create(MapView, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Map content for the MapControl.</p>


```csharp
public static MapControlContent Create(MapView mapView, Envelope initialExtent)
```
### Create(MapView, Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Map content for the MapControl.</p>


```csharp
public static MapControlContent Create(MapView mapView, Camera initialCamera)
```
### Create(IEnumerable&lt;Item&gt;, Envelope, MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Item content for the MapControl.</p>


```csharp
public static MapControlContent Create(IEnumerable<Item> items, Envelope initialExtent, MapViewingMode viewingMode)
```
### Create(IEnumerable&lt;Item&gt;, Camera, MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Item content for the MapControl.</p>


```csharp
public static MapControlContent Create(IEnumerable<Item> items, Camera initialCamera, MapViewingMode viewingMode)
```
### Create(IEnumerable&lt;Layer&gt;, Envelope, MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Layer content for the MapControl.</p>


```csharp
public static MapControlContent Create(IEnumerable<Layer> layers, Envelope initialExtent, MapViewingMode viewingMode)
```
### Create(IEnumerable&lt;Layer&gt;, Camera, MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Create Layer content for the MapControl.</p>


```csharp
public static MapControlContent Create(IEnumerable<Layer> layers, Camera initialCamera, MapViewingMode viewingMode)
```
### IsItemSupported(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControlContentFactory.yml" sourcestartlinenumber="1">Determines if the Item can be displayed by the MapControl.</p>


```csharp
public static bool IsItemSupported(Item item)
```


