# ParcelFabricExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">This convenience API provides commonly-used ParcelFabric-related extension methods.</p>


## Object Signature

```csharp
public static class ParcelFabricExtensions
```


## Members

### ClearActiveRecord(ParcelLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Clears the active record.</p>


```csharp
public static void ClearActiveRecord(this ParcelLayer parcelLayer)
```
### GetActiveRecord(ParcelLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the active record information.</p>


```csharp
public static ParcelRecord GetActiveRecord(this ParcelLayer parcelLayer)
```
### GetConnectionLinesLayerAsync(ParcelLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the connection lines layer for the given parcel layer.</p>


```csharp
public static Task<List<FeatureLayer>> GetConnectionLinesLayerAsync(this ParcelLayer parcelLayer)
```
### GetHistoricParcelLineLayerByTypeNameAsync(ParcelLayer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the historic line layer(s) for the given parcel type name.</p>


```csharp
public static Task<List<FeatureLayer>> GetHistoricParcelLineLayerByTypeNameAsync(this ParcelLayer parcelLayer, string typeName)
```
### GetHistoricParcelPolygonLayerByTypeNameAsync(ParcelLayer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the historic polygon layer(s) for the given parcel type name.</p>


```csharp
public static Task<List<FeatureLayer>> GetHistoricParcelPolygonLayerByTypeNameAsync(this ParcelLayer parcelLayer, string typeName)
```
### GetParcelFabric(ParcelLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the parcel fabric for the input parcel layer.</p>


```csharp
public static ParcelFabric GetParcelFabric(this ParcelLayer parcelLayer)
```
### GetParcelFeaturesAsync(ParcelLayer, SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the other related parcel features for the input parcels.</p>


```csharp
public static Task<ParcelFeatures> GetParcelFeaturesAsync(this ParcelLayer parcelLayer, SelectionSet parcelPolygonFeatures)
```
### GetParcelLineLayerByTypeNameAsync(ParcelLayer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the line layer(s) for the given parcel type name.</p>


```csharp
public static Task<List<FeatureLayer>> GetParcelLineLayerByTypeNameAsync(this ParcelLayer parcelLayer, string typeName)
```
### GetParcelPolygonLayerByTypeNameAsync(ParcelLayer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the polygon layer(s) for the given parcel type name.</p>


```csharp
public static Task<List<FeatureLayer>> GetParcelPolygonLayerByTypeNameAsync(this ParcelLayer parcelLayer, string typeName)
```
### GetParcelTypeNamesAsync(ParcelLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the parcel type names for the given parcel layer.</p>


```csharp
public static Task<List<string>> GetParcelTypeNamesAsync(this ParcelLayer parcelLayer)
```
### GetPointsLayerAsync(ParcelLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the points layer for the given parcel layer.</p>


```csharp
public static Task<List<FeatureLayer>> GetPointsLayerAsync(this ParcelLayer parcelLayer)
```
### GetRecordAsync(ParcelLayer, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the active record information.</p>


```csharp
public static Task<ParcelRecord> GetRecordAsync(this ParcelLayer parcelLayer, Guid guid)
```
### GetRecordAsync(ParcelLayer, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the active record information.</p>


```csharp
public static Task<ParcelRecord> GetRecordAsync(this ParcelLayer parcelLayer, long oid)
```
### GetRecordAsync(ParcelLayer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the active record information.</p>


```csharp
public static Task<ParcelRecord> GetRecordAsync(this ParcelLayer parcelLayer, string name)
```
### GetRecordsLayerAsync(ParcelLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets the records layer for the given parcel layer.</p>


```csharp
public static Task<List<FeatureLayer>> GetRecordsLayerAsync(this ParcelLayer parcelLayer)
```
### GetSequencedParcelEdgeInfoAsync(ParcelLayer, Layer, long, MapPoint, ParcelLineToEdgeRelationship)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets a clockwise ordered sequence of parcel edges, and their lines, in the same
parcel type as the input parcel, and filtering the result by specifying the
desired line-to-edge relationships.</p>


```csharp
public static Task<ParcelEdgeCollection> GetSequencedParcelEdgeInfoAsync(this ParcelLayer parcelLayer, Layer parcelTypePolygonLayer, long oid, MapPoint startPointHint, ParcelLineToEdgeRelationship edgeRelationshipFilter = -1)
```
### GetSequencedParcelEdgeInfoAsync(ParcelLayer, Layer, long, MapPoint, SequencedEdgeParcelParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets a clockwise ordered sequence of parcel edges, and their lines, in the same
parcel type as the input parcel, and filtering the result by specifying the
desired line-to-edge relationships.</p>


```csharp
public static Task<ParcelEdgeCollection> GetSequencedParcelEdgeInfoAsync(this ParcelLayer parcelLayer, Layer parcelTypePolygonLayer, long oid, MapPoint startPointHint, SequencedEdgeParcelParams sequenceParams)
```
### GetSequencedParcelEdgeInfoAsync(ParcelLayer, Layer, long, MapPoint, double, ParcelLineToEdgeRelationship)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Gets a clockwise ordered sequence of parcel edges, and their lines, in the same
parcel type as the input parcel, and filtering the result by specifying the
desired line-to-edge relationships.</p>


```csharp
public static Task<ParcelEdgeCollection> GetSequencedParcelEdgeInfoAsync(this ParcelLayer parcelLayer, Layer parcelTypePolygonLayer, long oid, MapPoint startPointHint, double offsetTolerance, ParcelLineToEdgeRelationship edgeRelationshipFilter = -1)
```
### SetActiveRecord(ParcelLayer, ParcelRecord)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Sets the active record.</p>


```csharp
public static bool SetActiveRecord(this ParcelLayer parcelLayer, ParcelRecord parcelRecord)
```
### SetActiveRecordAsync(ParcelLayer, ParcelRecord)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Sets the active record.</p>


```csharp
public static Task<bool> SetActiveRecordAsync(this ParcelLayer parcelLayer, ParcelRecord parcelRecord)
```
### SetActiveRecordAsync(ParcelLayer, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Sets the active record.</p>


```csharp
public static Task<bool> SetActiveRecordAsync(this ParcelLayer parcelLayer, Guid guid)
```
### SetActiveRecordAsync(ParcelLayer, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Sets the active record.</p>


```csharp
public static Task<bool> SetActiveRecordAsync(this ParcelLayer parcelLayer, long oid)
```
### SetActiveRecordAsync(ParcelLayer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ParcelFabricExtensions.yml" sourcestartlinenumber="1">Sets the active record.</p>


```csharp
public static Task<bool> SetActiveRecordAsync(this ParcelLayer parcelLayer, string name)
```


