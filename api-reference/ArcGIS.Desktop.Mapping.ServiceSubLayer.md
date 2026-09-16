# ServiceSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Represents sub layers within a service layer.</p>


## Object Signature

```csharp
public sealed class ServiceSubLayer : Layer, IMetadataInfo, IMetadataSource
```


## Members

### BackingFeatureLayerID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Gets the Backing FeatureLayer ID for a ServiceSubLayer.</p>


```csharp
public int BackingFeatureLayerID { get; set; }
```
### CurrentRepresentationClassName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Represents sub layers within a service layer.</p>


```csharp
public string CurrentRepresentationClassName { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query.</p>


```csharp
public string DefinitionQuery { get; }
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Gets the layer's definition which is null for service sublayers.</p>


```csharp
public override CIMBaseLayer GetDefinition()
```
### GetOwningServiceLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Returns the Service Layer which owns this sub layer.</p>


```csharp
public ServiceLayer GetOwningServiceLayer()
```
### GetRenderer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Returns the renderer used to draw the feature scene layer
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRenderer GetRenderer()
```
### HasNonSpatialTracks

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Represents sub layers within a service layer.</p>


```csharp
public bool HasNonSpatialTracks { get; }
```
### IsLabelVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Gets whether labels are drawing.</p>


```csharp
public bool IsLabelVisible { get; }
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Gets whether the layer is selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### PreviousObservationsCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Represents sub layers within a service layer.</p>


```csharp
public int PreviousObservationsCount { get; }
```
### RepresentationClassNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Represents sub layers within a service layer.</p>


```csharp
public string[] RepresentationClassNames { get; }
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Sets the display name for the layer, however this method is not supported for this layer type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override void SetName(string newName)
```
### ShapeType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Gets the service sublayers's shape type.</p>


```csharp
public esriGeometryType ShapeType { get; }
```
### ShowPreviousObservations

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Represents sub layers within a service layer.</p>


```csharp
public bool ShowPreviousObservations { get; }
```
### ShowTrackLines

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Represents sub layers within a service layer.</p>


```csharp
public bool ShowTrackLines { get; }
```
### SourceLayerType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Gets the Source Layer Type for a ServiceSubLayer.</p>


```csharp
public ServiceSubLayerSourceLayerType SourceLayerType { get; }
```
### SupportsMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Gets whether the ServiceSubLayer supports metadata</p>


```csharp
public override bool SupportsMetadata { get; }
```
### TrackIdFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubLayer.yml" sourcestartlinenumber="1">Represents sub layers within a service layer.</p>


```csharp
public string TrackIdFieldName { get; }
```


