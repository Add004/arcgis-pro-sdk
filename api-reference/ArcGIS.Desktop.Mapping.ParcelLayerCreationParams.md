# ParcelLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a parcel layer with pre-defined properties.</p>


## Object Signature

```csharp
public class ParcelLayerCreationParams : LayerCreationParams
```


## Members

### ParcelLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ParcelLayerCreationParams(CIMDataConnection dataConnection)
```
### ParcelLayerCreationParams(ParcelFabric)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.Parcels.ParcelFabric" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ParcelLayerCreationParams(ParcelFabric parcelFabric)
```
### ParcelLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ParcelLayerCreationParams(Item item)
```
### ParcelLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ParcelLayerCreationParams(Uri uri)
```
### AddAssociatedLayers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets whether the parcel associated layers are to be added along with the parcel layer. Default value is true.</p>


```csharp
public bool AddAssociatedLayers { get; set; }
```
### LayerCreationRole

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelLayerCreationParams.yml" sourcestartlinenumber="1">Defines the role for the added parcel layers.
Default value is ParcelLayerCreationRole.ParcelEditingLayers</p>


```csharp
public ParcelLayerCreationRole LayerCreationRole { get; set; }
```
### ParcelFabric

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelLayerCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Parcels.ParcelFabric" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ParcelFabric ParcelFabric { get; protected set; }
```


