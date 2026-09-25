# EditOperation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">EditOperations are shortlived objects for performing an Edit, they are generally immediately filled with the parameters of the desired edit and executed then
they are discarded after the editor executes them...</p>


## Object Signature

```csharp
public sealed class EditOperation : IEditorOperation
```


## Members

### EditOperation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Constructs a new EditOperation representing an edit to be performed against the Geodatabase.</p>


```csharp
public EditOperation()
```
### Abort()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Mark the Edit Operation as aborted.</p>


```csharp
public void Abort()
```
### AddAttachment(Table, long, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Add an attachment to a row/feature with attachment support.</p>


```csharp
public void AddAttachment(Table table, long oid, string filePath)
```
### AddAttachment(Table, long, string, AttachmentProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Add an attachment to a row/feature with attachment support.</p>


```csharp
public void AddAttachment(Table table, long oid, string filePath, AttachmentProperties properties)
```
### AddAttachment(RowHandle, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Add an attachment to a row/feature with attachment support.</p>


```csharp
public void AddAttachment(RowHandle row, string filePath)
```
### AddAttachment(RowHandle, string, AttachmentProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Add an attachment to a row/feature with attachment support.</p>


```csharp
public void AddAttachment(RowHandle row, string filePath, AttachmentProperties properties)
```
### AddAttachment(RowToken, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Add an attachment to a row with attachment support.</p>


```csharp
public void AddAttachment(RowToken token, string filePath)
```
### AddAttachment(RowToken, string, AttachmentProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Add an attachment to a row with attachment support.</p>


```csharp
public void AddAttachment(RowToken token, string filePath, AttachmentProperties properties)
```
### AddAttachment(MapMember, long, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Add an attachment to a row/feature with attachment support.</p>


```csharp
public void AddAttachment(MapMember mapMember, long oid, string filePath)
```
### AddAttachment(MapMember, long, string, AttachmentProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Add an attachment to a row/feature with attachment support.</p>


```csharp
public void AddAttachment(MapMember mapMember, long oid, string filePath, AttachmentProperties properties)
```
### AssignFeaturesToRecord(ParcelLayer, SelectionSet, ParcelRecord)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Assign parcels to a record.</p>


```csharp
public ParcelEditToken AssignFeaturesToRecord(ParcelLayer parcelLayer, SelectionSet sourceFeatures, ParcelRecord parcelRecord)
```
### AssignFeaturesToRecord(ParcelLayer, SelectionSet, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Assign parcels to a record.</p>


```csharp
public ParcelEditToken AssignFeaturesToRecord(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Guid recordGuid)
```
### AssignFeaturesToRecord(ParcelLayer, SelectionSet, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Assign parcels to a record.</p>


```csharp
public ParcelEditToken AssignFeaturesToRecord(ParcelLayer parcelLayer, SelectionSet sourceFeatures, long recordOid)
```
### AssignFeaturesToRecord(ParcelLayer, SelectionSet, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Assign parcels to a record.</p>


```csharp
public ParcelEditToken AssignFeaturesToRecord(ParcelLayer parcelLayer, SelectionSet sourceFeatures, string recordName)
```
### AutoComplete(EditingTemplate, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Create a new feature by auto-complete.</p>


```csharp
public void AutoComplete(EditingTemplate template, Geometry autoCompleteGeometry)
```
### AutoComplete(Layer, Geometry, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Create a new feature by auto-complete.</p>


```csharp
public void AutoComplete(Layer layer, Geometry autoCompleteGeometry, Dictionary<string, object> values = null)
```
### BuildParcelsByExtent(ParcelLayer, Envelope, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Build parcel features within the given extent of the parcel layer.</p>


```csharp
public ParcelEditToken BuildParcelsByExtent(ParcelLayer parcelLayer, Envelope extent, IEnumerable<MapMember> layers = null)
```
### BuildParcelsByRecord(ParcelLayer, Guid, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Build parcel features that are assigned to the specified record.</p>


```csharp
public ParcelEditToken BuildParcelsByRecord(ParcelLayer parcelLayer, Guid recordGuid, IEnumerable<MapMember> layers = null)
```
### Callback(Action&lt;IEditContext&gt;, Dataset)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Registers that the edit operation will callback into the given function in the context of an edit operation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Callback(Action<EditOperation.IEditContext> action, Dataset dataset)
```
### Callback(Action&lt;IEditContext&gt;, params Dataset[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Registers that the edit operation will callback into the given function in the context of an edit operation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Callback(Action<EditOperation.IEditContext> action, params Dataset[] datasets)
```
### Callback(Action&lt;IEditContext&gt;, MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Registers that the edit operation will callback into the given function in the context of an edit operation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Callback(Action<EditOperation.IEditContext> action, MapMember mapMember)
```
### Callback(Action&lt;IEditContext&gt;, params MapMember[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Registers that the edit operation will callback into the given function in the context of an edit operation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Callback(Action<EditOperation.IEditContext> action, params MapMember[] mapMembers)
```
### Callback(Action&lt;IEditContext&gt;, IEnumerable&lt;Dataset&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Registers that the edit operation will callback into the given function in the context of an edit operation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Callback(Action<EditOperation.IEditContext> action, IEnumerable<Dataset> datasets)
```
### Callback(Action&lt;IEditContext&gt;, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Registers that the edit operation will callback into the given function in the context of an edit operation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Callback(Action<EditOperation.IEditContext> action, IEnumerable<MapMember> mapMembers)
```
### CanCreateTraverse(Traverse, EditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Determines if the features can be created for the traverse using the specified template.</p>


```csharp
public bool CanCreateTraverse(Traverse traverse, EditingTemplate featureTemplate)
```
### CancelMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets the cancel message.</p>


```csharp
public string CancelMessage { get; set; }
```
### ChangeParcelType(ParcelLayer, SelectionSet, Layer, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Change the parcel type of selected parcels.</p>


```csharp
public ParcelEditToken ChangeParcelType(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Layer destinationPolygonLayer, Layer destinationLineLayer = null)
```
### ChangeParcelType(ParcelLayer, SelectionSet, Layer, int, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Change the parcel type of selected parcels.</p>


```csharp
public ParcelEditToken ChangeParcelType(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Layer destinationPolygonLayer, int destinationParcelSubtype, Layer destinationLineLayer = null)
```
### Clip(Layer, IEnumerable&lt;long&gt;, Geometry, ClipMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Clip a set of features with a geometry.</p>


```csharp
public void Clip(Layer layer, IEnumerable<long> oids, Geometry clippingGeometry, ClipMode clipMode = ClipMode.PreserveArea)
```
### Clip(Layer, IEnumerable&lt;long&gt;, Geometry, ClipMode, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Clip a set of features with a geometry.</p>


```csharp
public void Clip(Layer layer, IEnumerable<long> oids, Geometry clippingGeometry, ClipMode clipMode, bool keepCoincident)
```
### Clip(Layer, long, Geometry, ClipMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Clip a feature with a geometry.</p>


```csharp
public void Clip(Layer layer, long oid, Geometry clippingGeometry, ClipMode clipMode = ClipMode.PreserveArea)
```
### ConstructPolygons(EditingTemplate, Layer, IEnumerable&lt;long&gt;, double?, LinearUnit, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Constructs polygons in a template using the specified polylines.</p>


```csharp
public void ConstructPolygons(EditingTemplate template, Layer layer, IEnumerable<long> oids, double? tolerance, LinearUnit toleranceUnit, bool autoComplete)
```
### ConstructPolygons(EditingTemplate, Layer, IEnumerable&lt;long&gt;, double?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Constructs polygons in a template using the specified polylines.</p>


```csharp
public void ConstructPolygons(EditingTemplate template, Layer layer, IEnumerable<long> oids, double? tolerance, bool autoComplete)
```
### ConstructPolygons(EditingTemplate, SelectionSet, double?, LinearUnit, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Constructs polygons in a template using the specified polylines.</p>


```csharp
public void ConstructPolygons(EditingTemplate template, SelectionSet features, double? tolerance, LinearUnit toleranceUnit, bool autoComplete)
```
### ConstructPolygons(EditingTemplate, SelectionSet, double?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Constructs polygons in a template using the specified polylines.</p>


```csharp
public void ConstructPolygons(EditingTemplate template, SelectionSet features, double? tolerance, bool autoComplete)
```
### Copy(MapMember, MapMember, IEnumerable&lt;long&gt;, int?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Copies the specified rows from the source mapMember to the destination mapMember.</p>


```csharp
public void Copy(MapMember destinationMapMember, MapMember sourceMapMember, IEnumerable<long> oids, int? subtypeCode = null)
```
### CopyLineFeaturesToParcelType(Layer, IEnumerable&lt;long&gt;, Layer, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Copies rows with the given IDs from the source to the destination.
This function is for copying lines to parcel fabrics.
Lines forming enclosed areas will have parcel seeds created within each area.</p>


```csharp
public ParcelEditToken CopyLineFeaturesToParcelType(Layer sourceLayer, IEnumerable<long> sourceOIDs, Layer destinationLineLayer, Layer destinationPolygonLayer)
```
### CopyLineFeaturesToParcelType(Layer, IEnumerable&lt;long&gt;, Layer, Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Copies rows with the given IDs from the source to the destination.
This function is for copying lines to parcel fabrics.
Lines forming enclosed areas will have parcel seeds created within each area.</p>


```csharp
public ParcelEditToken CopyLineFeaturesToParcelType(Layer sourceLayer, IEnumerable<long> sourceOIDs, Layer destinationLineLayer, Layer destinationPolygonLayer, int subtypeCode)
```
### CopyParcelLinesToParcelType(ParcelLayer, SelectionSet, Layer, Layer, bool, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Copy line feature to parcel type.</p>


```csharp
public ParcelEditToken CopyParcelLinesToParcelType(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Layer destinationLineLayer, Layer destinationPolygonLayer, bool markParentsAsHistoric = true, bool useSourceLineAttributes = true, bool useSourcePolygonAttributes = true)
```
### CopyParcelLinesToParcelType(ParcelLayer, SelectionSet, Layer, Layer, int, bool, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Copy line feature to parcel type.</p>


```csharp
public ParcelEditToken CopyParcelLinesToParcelType(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Layer destinationLineLayer, Layer destinationPolygonLayer, int parcelSubtype, bool markParentsAsHistoric = true, bool useSourceLineAttributes = true, bool useSourcePolygonAttributes = true)
```
### Create(Table)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new row in the specified table.</p>


```csharp
public RowToken Create(Table table)
```
### Create(Table, KnowledgeGraphDocumentDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new row in the Knowledge Graph Document table for the specified properties in the KnowledgeGraphDocumentDescription.</p>


```csharp
public RowToken Create(Table documentTable, KnowledgeGraphDocumentDescription documentDescription)
```
### Create(Table, KnowledgeGraphRelationshipDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new relationship between the two specified entities in the KnowledgeGraphRelationshipDescription.</p>


```csharp
public void Create(Table relationshipTable, KnowledgeGraphRelationshipDescription relationshipDescription)
```
### Create(Table, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new row with the given attributes.</p>


```csharp
public RowToken Create(Table table, Dictionary<string, object> values)
```
### Create(AssociationDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a utility network association.</p>


```csharp
public void Create(AssociationDescription associationDescription)
```
### Create(KnowledgeGraphProvenanceDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new provenance record with the information in the <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void Create(KnowledgeGraphProvenanceDescription provenanceDescription)
```
### Create(ParallelOffset)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates new features copied parallel to the selected features in the
<xref href="ArcGIS.Desktop.Editing.ParallelOffset.Selection" data-throw-if-not-resolved="false"></xref></p>


```csharp
public void Create(ParallelOffset offset)
```
### Create(Builder)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates new features copied parallel to the selected features in the
<xref href="ArcGIS.Desktop.Editing.ParallelOffset.Selection" data-throw-if-not-resolved="false"></xref>. A ParallelOffset is created
from the input builder.</p>


```csharp
public void Create(ParallelOffset.Builder builder)
```
### Create(RelationshipDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new relationship between the two specified rows in the RelationshipDescription.</p>


```csharp
public void Create(RelationshipDescription relationshipDescription)
```
### Create(EditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new row using the given template.</p>


```csharp
public RowToken Create(EditingTemplate template)
```
### Create(EditingTemplate, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new feature using the given template and geometry.</p>


```csharp
public RowToken Create(EditingTemplate template, Geometry geometry)
```
### Create(Layer, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new feature in the given layer given a geometry with default geodatabase values.</p>


```csharp
public RowToken Create(Layer layer, Geometry geometry)
```
### Create(Layer, Geometry, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new feature in the given layer given a geometry and a set of attributes.</p>


```csharp
public RowToken Create(Layer layer, Geometry geometry, Dictionary<string, object> values)
```
### Create(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new row with default geodatabase values.</p>


```csharp
public RowToken Create(MapMember mapMember)
```
### Create(MapMember, Inspector)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new row with the given inspector.</p>


```csharp
public RowToken Create(MapMember mapMember, Inspector inspector)
```
### Create(MapMember, KnowledgeGraphDocumentDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new row in the Knowledge Graph Document table for the specified properties in the KnowledgeGraphDocumentDescription.</p>


```csharp
public RowToken Create(MapMember documentMapMember, KnowledgeGraphDocumentDescription documentDescription)
```
### Create(MapMember, KnowledgeGraphRelationshipDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new relationship between the two specified entities in the KnowledgeGraphRelationshipDescription.</p>


```csharp
public void Create(MapMember relationshipMapMember, KnowledgeGraphRelationshipDescription relationshipDescription)
```
### Create(MapMember, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new row with the given attributes.</p>


```csharp
public RowToken Create(MapMember mapMember, Dictionary<string, object> values)
```
### CreateChainedOperation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a follow-on operation which will be shared with this operation on the
application's undo stack.</p>


```csharp
public EditOperation CreateChainedOperation()
```
### CreateEx(Table, KnowledgeGraphRelationshipDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new relationship between the two specified entities in the KnowledgeGraphRelationshipDescription.</p>


```csharp
public RowToken CreateEx(Table relationshipTable, KnowledgeGraphRelationshipDescription relationshipDescription)
```
### CreateEx(KnowledgeGraphProvenanceDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new provenance record with the information in the <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RowToken CreateEx(KnowledgeGraphProvenanceDescription provenanceDescription)
```
### CreateEx(MapMember, KnowledgeGraphRelationshipDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates a new relationship between the two specified entities in the KnowledgeGraphRelationshipDescription.</p>


```csharp
public RowToken CreateEx(MapMember relationshipMapMember, KnowledgeGraphRelationshipDescription relationshipDescription)
```
### CreateParcelSeedsByRecord(ParcelLayer, Guid, Envelope, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Create parcel seeds for all lines with the given extent and record.</p>


```csharp
public ParcelEditToken CreateParcelSeedsByRecord(ParcelLayer parcelLayer, Guid recordGuid, Envelope extent, IEnumerable<MapMember> layers = null)
```
### CreateParcelSeedsByRecord(ParcelLayer, Guid, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Create parcel seeds for all lines with the given record.</p>


```csharp
public ParcelEditToken CreateParcelSeedsByRecord(ParcelLayer parcelLayer, Guid recordGuid, IEnumerable<MapMember> layers = null)
```
### CreateTraverse(Traverse, EditingTemplate, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Creates features using the traverse courses and the specified feature template.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task CreateTraverse(Traverse traverse, EditingTemplate featureTemplate, Dictionary<string, object> values = null)
```
### Delete(Row)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Delete a row.</p>


```csharp
public void Delete(Row row)
```
### Delete(Table, KnowledgeGraphRelationshipDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Deletes a relationship between the two specified entities in the KnowledgeGraphRelationshipDescription.</p>


```csharp
public void Delete(Table relationshipTable, KnowledgeGraphRelationshipDescription relationshipDescription)
```
### Delete(Table, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Delete rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Delete(Table table, IEnumerable<long> oids)
```
### Delete(Table, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Delete a row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Delete(Table table, long oid)
```
### Delete(AssociationDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Deletes a utility network association.</p>


```csharp
public void Delete(AssociationDescription associationDescription)
```
### Delete(RelationshipDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Deletes the relationship that associates the two specified rows in the RelationshipDescription.</p>


```csharp
public void Delete(RelationshipDescription relationshipDescription)
```
### Delete(MapMember, KnowledgeGraphRelationshipDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Deletes a relationship between the two specified entities in the KnowledgeGraphRelationshipDescription.</p>


```csharp
public void Delete(MapMember relationshipMapMember, KnowledgeGraphRelationshipDescription relationshipDescription)
```
### Delete(MapMember, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Delete features or rows.</p>


```csharp
public void Delete(MapMember mapMember, IEnumerable<long> oids)
```
### Delete(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Delete a feature or row.</p>


```csharp
public void Delete(MapMember mapMember, long oid)
```
### Delete(SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Delete the set of rows.</p>


```csharp
public void Delete(SelectionSet rows)
```
### Delete(IEnumerable&lt;Row&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Delete rows.</p>


```csharp
public void Delete(IEnumerable<Row> rows)
```
### DeleteParcels(Layer, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Delete parcel polygon features.</p>


```csharp
public void DeleteParcels(Layer layer, IEnumerable<long> oids)
```
### Duplicate(Layer, long, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Adds an edit operation that creates a duplicate of the specified feature with given geometry offsets.</p>


```csharp
public void Duplicate(Layer layer, long oid, double xOffset, double yOffset, double zOffset)
```
### DuplicateParcels(ParcelLayer, SelectionSet, ParcelRecord, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, ParcelRecord parcelRecord, Layer destinationLayer)
```
### DuplicateParcels(ParcelLayer, SelectionSet, ParcelRecord, Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, ParcelRecord parcelRecord, Layer destinationLayer, int destinationParcelSubtype)
```
### DuplicateParcels(ParcelLayer, SelectionSet, ParcelRecord, Layer, int, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, ParcelRecord parcelRecord, Layer destinationLayer, int destinationParcelSubtype, long repeatCount)
```
### DuplicateParcels(ParcelLayer, SelectionSet, ParcelRecord, Layer, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, ParcelRecord parcelRecord, Layer destinationLayer, long repeatCount)
```
### DuplicateParcels(ParcelLayer, SelectionSet, Guid, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Guid recordGuid, Layer destinationLayer)
```
### DuplicateParcels(ParcelLayer, SelectionSet, Guid, Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Guid recordGuid, Layer destinationLayer, int destinationParcelSubtype)
```
### DuplicateParcels(ParcelLayer, SelectionSet, Guid, Layer, int, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Guid recordGuid, Layer destinationLayer, int destinationParcelSubtype, long repeatCount)
```
### DuplicateParcels(ParcelLayer, SelectionSet, Guid, Layer, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Guid recordGuid, Layer destinationLayer, long repeatCount)
```
### DuplicateParcels(ParcelLayer, SelectionSet, long, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, long recordOid, Layer destinationLayer)
```
### DuplicateParcels(ParcelLayer, SelectionSet, long, Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, long recordOid, Layer destinationLayer, int destinationParcelSubtype)
```
### DuplicateParcels(ParcelLayer, SelectionSet, long, Layer, int, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, long recordOid, Layer destinationLayer, int destinationParcelSubtype, long repeatCount)
```
### DuplicateParcels(ParcelLayer, SelectionSet, long, Layer, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, long recordOid, Layer destinationLayer, long repeatCount)
```
### DuplicateParcels(ParcelLayer, SelectionSet, string, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, string recordName, Layer destinationLayer)
```
### DuplicateParcels(ParcelLayer, SelectionSet, string, Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, string recordName, Layer destinationLayer, int destinationParcelSubtype)
```
### DuplicateParcels(ParcelLayer, SelectionSet, string, Layer, int, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, string recordName, Layer destinationLayer, int destinationParcelSubtype, long repeatCount)
```
### DuplicateParcels(ParcelLayer, SelectionSet, string, Layer, int, long, string, long, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, string recordName, Layer destinationLayer, int destinationParcelSubtype, long repeatCount, string updateField, long startValue, long incrementValue)
```
### DuplicateParcels(ParcelLayer, SelectionSet, string, Layer, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Duplicate the selected parcels.</p>


```csharp
public ParcelEditToken DuplicateParcels(ParcelLayer parcelLayer, SelectionSet sourceFeatures, string recordName, Layer destinationLayer, long repeatCount)
```
### EditOperationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets the transaction type for the EditOperation.</p>


```csharp
public EditOperationType? EditOperationType { get; set; }
```
### ErrorMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets the ErrorMessage.</p>


```csharp
public string ErrorMessage { get; set; }
```
### EventToken

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Provides a way for calling code to identify a particular EditOperation within a subsequent <xref href="ArcGIS.Desktop.Editing.Events.EditCompletedEvent?text=EditEvent" data-throw-if-not-resolved="false"></xref>.
Setting an EventToken in an EditOperation is optional - by default it is null.
If set to a non-null object, the EditOperation is subsequently successful, and, an EditEvent is published,
then the EventToken object set here, will be available from the corresponding <xref href="ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.EventToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public object EventToken { get; set; }
```
### Execute()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Executes the Edit, modifying the database using the instructions given to the EditOperation.  Returns true upon success and
false upon failure.</p>


```csharp
public bool Execute()
```
### ExecuteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Executes the Edit, modifying the database using the instructions given to the EditOperation.  Returns true upon success and
false upon failure.</p>


```csharp
public Task<bool> ExecuteAsync()
```
### ExecuteMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets the execute mode for the operation. Default value is <xref href="ArcGIS.Desktop.Editing.ExecuteModeType.Default" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ExecuteModeType ExecuteMode { get; set; }
```
### Explode(Layer, IEnumerable&lt;long&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Explode features.</p>


```csharp
public void Explode(Layer layer, IEnumerable<long> oids, bool keepOriginalFeature = true)
```
### Explode(Layer, long, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Explode a feature.</p>


```csharp
public void Explode(Layer layer, long oid, bool keepOriginalFeature = true)
```
### ~EditOperation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Finalizer for EditOperation.</p>


```csharp
protected ~EditOperation()
```
### GetAwaiter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">This method is intended for compiler use rather than for use in application code. The presence of this method allows an EditOperation to be 'await'-ed like a
Task (the Task returned by calling ExecuteAsync()).</p>


```csharp
public TaskAwaiter<bool> GetAwaiter()
```
### IsCanceled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets a value indicating if the EditOperation has been Canceled.  EditOperations are marked as Canceled when they have been Executed but canceled before completing and not performed.</p>


```csharp
public bool IsCanceled { get; }
```
### IsDone

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets a value indicating if the EditOperation is Done. EditOperations are marked as Done when someone calls ExecuteAsync() on them (even before they are complete).</p>


```csharp
public bool IsDone { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets a value indicating if the EditOperation is empty.</p>


```csharp
public bool IsEmpty { get; }
```
### IsSucceeded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets a value indicating if the EditOperation Succeeded. EditOperations are marked as Succeeded when ExecuteAsync() succeeds (the Task terminates with true).</p>


```csharp
public bool IsSucceeded { get; }
```
### Merge(EditingRowTemplate, Layer, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Merge features into a new feature defined by a feature template.</p>


```csharp
public void Merge(EditingRowTemplate template, Layer sourceLayer, IEnumerable<long> sourceOIDs)
```
### Merge(Layer, Layer, IEnumerable&lt;long&gt;, Inspector)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Merge features into a new feature in the <code class="paramref">destinationLayer</code> with attributes.</p>


```csharp
public void Merge(Layer destinationLayer, Layer sourceLayer, IEnumerable<long> sourceOIDs, Inspector inspector = null)
```
### Merge(Layer, IEnumerable&lt;long&gt;, Inspector)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Merge features within a layer into an existing feature with attributes.  The first feature in the <code class="paramref">sourceOIDs</code>
will be the feature that is retained and contain the merge result.</p>


```csharp
public void Merge(Layer sourceLayer, IEnumerable<long> sourceOIDs, Inspector inspector = null)
```
### Modify(Row, Dictionary&lt;int, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(Row row, Dictionary<int, object> attributes)
```
### Modify(Row, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(Row row, Dictionary<string, object> attributes)
```
### Modify(Row, int, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(Row row, int fieldIndex, object value)
```
### Modify(Row, string, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(Row row, string fieldName, object value)
```
### Modify(Table, long, Dictionary&lt;int, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(Table table, long oid, Dictionary<int, object> attributes)
```
### Modify(Table, long, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(Table table, long oid, Dictionary<string, object> attributes)
```
### Modify(Table, long, int, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(Table table, long oid, int fieldIndex, object value)
```
### Modify(Table, long, string, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(Table table, long oid, string fieldName, object value)
```
### Modify(Inspector)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a feature or row defined by an inspector object.</p>


```csharp
public void Modify(Inspector inspector)
```
### Modify(Layer, long, Geometry, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a feature, updating the geometry and attribute values.</p>


```csharp
public void Modify(Layer layer, long oid, Geometry geometry, Dictionary<string, object> attributes = null)
```
### Modify(MapMember, long, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Modify a row, updating the attribute values.</p>


```csharp
public void Modify(MapMember mapMember, long oid, Dictionary<string, object> attributes)
```
### Move(Layer, IEnumerable&lt;long&gt;, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Moves a collection of features along the same vector.</p>


```csharp
public void Move(Layer layer, IEnumerable<long> oids, double dx, double dy)
```
### Move(Layer, IEnumerable&lt;long&gt;, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Moves a collection of features along the same vector.</p>


```csharp
public void Move(Layer layer, IEnumerable<long> oids, double dx, double dy, double dz)
```
### Move(Layer, long, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Moves a feature along a vector.</p>


```csharp
public void Move(Layer layer, long oid, double dx, double dy)
```
### Move(Layer, long, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Moves a feature along a vector.</p>


```csharp
public void Move(Layer layer, long oid, double dx, double dy, double dz)
```
### Move(SelectionSet, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Moves a set of features all along the same vector.</p>


```csharp
public void Move(SelectionSet features, double dx, double dy)
```
### Move(SelectionSet, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Moves a set of features all along the same vector.</p>


```csharp
public void Move(SelectionSet features, double dx, double dy, double dz)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets the string reported to the application's undo stack for this EditOperation.</p>


```csharp
public string Name { get; set; }
```
### Planarize(Layer, IEnumerable&lt;long&gt;, double, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Planarize features.</p>


```csharp
public void Planarize(Layer layer, IEnumerable<long> oids, double clusterTolerance, LinearUnit clusterToleranceUnit)
```
### Planarize(Layer, IEnumerable&lt;long&gt;, double?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Planarize features.</p>


```csharp
public void Planarize(Layer layer, IEnumerable<long> oids, double? clusterTolerance = null)
```
### Planarize(Layer, long, double, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Planarize features.</p>


```csharp
public void Planarize(Layer layer, long oid, double clusterTolerance, LinearUnit clusterToleranceUnit)
```
### Planarize(Layer, long, double?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Planarize a feature.</p>


```csharp
public void Planarize(Layer layer, long oid, double? clusterTolerance = null)
```
### ProgressMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets the string to show while executing this operation.</p>


```csharp
public string ProgressMessage { get; set; }
```
### ReassignFeaturesToRecord(ParcelLayer, ParcelRecord, ParcelRecord, bool, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Reassign parcels to another record.</p>


```csharp
public ParcelEditToken ReassignFeaturesToRecord(ParcelLayer parcelLayer, ParcelRecord sourceParcelRecord, ParcelRecord targetParcelRecord, bool deleteSourceRecord, IEnumerable<MapMember> layers = null)
```
### ReassignFeaturesToRecord(ParcelLayer, Guid, Guid, bool, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Reassign parcels to another record.</p>


```csharp
public ParcelEditToken ReassignFeaturesToRecord(ParcelLayer parcelLayer, Guid sourceRecordGuid, Guid targetRecordGuid, bool deleteSourceRecord, IEnumerable<MapMember> layers = null)
```
### ReassignFeaturesToRecord(ParcelLayer, long, long, bool, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Reassign parcels to another record.</p>


```csharp
public ParcelEditToken ReassignFeaturesToRecord(ParcelLayer parcelLayer, long sourceRecordOid, long targetRecordOid, bool deleteSourceRecord, IEnumerable<MapMember> layers = null)
```
### ReassignFeaturesToRecord(ParcelLayer, string, string, bool, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Reassign parcels to another record.</p>


```csharp
public ParcelEditToken ReassignFeaturesToRecord(ParcelLayer parcelLayer, string sourceRecordName, string targetRecordName, bool deleteSourceRecord, IEnumerable<MapMember> layers = null)
```
### ReconstructParcelsFromSeeds(ParcelLayer, Envelope, IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Reconstruct all parcel seeds within the given extent of the parcel layer.</p>


```csharp
public ParcelEditToken ReconstructParcelsFromSeeds(ParcelLayer parcelLayer, Envelope extent, IEnumerable<MapMember> layers = null)
```
### RedoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Attempts to Redo this EditOperation (only the most recently undone edit operation can be redone).</p>


```csharp
public Task<bool> RedoAsync()
```
### RemoveAllAttachments(Table, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Remove all attachments from a row/feature with attachment support.</p>


```csharp
public void RemoveAllAttachments(Table table, long oid)
```
### RemoveAllAttachments(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Remove all attachments from a row/feature with attachment support.</p>


```csharp
public void RemoveAllAttachments(MapMember mapMember, long oid)
```
### RemoveAttachment(Table, long, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Remove an attachment from a row/feature with attachment support.</p>


```csharp
public void RemoveAttachment(Table table, long oid, long attachmentOID)
```
### RemoveAttachment(MapMember, long, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Remove an attachment from a row/feature with attachment support.</p>


```csharp
public void RemoveAttachment(MapMember mapMember, long oid, long attachmentOID)
```
### Reshape(Layer, IEnumerable&lt;long&gt;, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Reshape features with a geometry.</p>


```csharp
public void Reshape(Layer layer, IEnumerable<long> oids, Geometry reshapeGeometry)
```
### Reshape(Layer, long, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Reshape a feature with a geometry.</p>


```csharp
public void Reshape(Layer layer, long oid, Geometry reshapeGeometry)
```
### Reshape(SelectionSet, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Reshape a set of features with a geometry.</p>


```csharp
public void Reshape(SelectionSet features, Geometry reshapeGeometry)
```
### RetireFeaturesToRecord(ParcelLayer, SelectionSet, ParcelRecord)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Retire parcels to a record.</p>


```csharp
public ParcelEditToken RetireFeaturesToRecord(ParcelLayer parcelLayer, SelectionSet sourceFeatures, ParcelRecord parcelRecord)
```
### RetireFeaturesToRecord(ParcelLayer, SelectionSet, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Retire parcels to a record.</p>


```csharp
public ParcelEditToken RetireFeaturesToRecord(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Guid recordGuid)
```
### RetireFeaturesToRecord(ParcelLayer, SelectionSet, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Retire parcels to a record.</p>


```csharp
public ParcelEditToken RetireFeaturesToRecord(ParcelLayer parcelLayer, SelectionSet sourceFeatures, long recordOid)
```
### RetireFeaturesToRecord(ParcelLayer, SelectionSet, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Retire parcels to a record.</p>


```csharp
public ParcelEditToken RetireFeaturesToRecord(ParcelLayer parcelLayer, SelectionSet sourceFeatures, string recordName)
```
### Rotate(Layer, IEnumerable&lt;long&gt;, MapPoint, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Rotates a collection of features.</p>


```csharp
public void Rotate(Layer layer, IEnumerable<long> oids, MapPoint origin, double angle)
```
### Rotate(Layer, long, MapPoint, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Rotates a feature.</p>


```csharp
public void Rotate(Layer layer, long oid, MapPoint origin, double angle)
```
### Rotate(SelectionSet, MapPoint, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Rotates a set of features.</p>


```csharp
public void Rotate(SelectionSet features, MapPoint origin, double angle)
```
### Rubbersheet(Layer, RubbersheetMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Rubbersheet a layer.</p>


```csharp
public void Rubbersheet(Layer layer, RubbersheetMethod rubbersheetMethod)
```
### Rubbersheet(SelectionSet, RubbersheetMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Rubbersheet the set of features.</p>


```csharp
public void Rubbersheet(SelectionSet features, RubbersheetMethod rubbersheetMethod)
```
### Scale(Layer, IEnumerable&lt;long&gt;, MapPoint, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Scales a collection of features.</p>


```csharp
public void Scale(Layer layer, IEnumerable<long> oids, MapPoint origin, double sx, double sy)
```
### Scale(Layer, IEnumerable&lt;long&gt;, MapPoint, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Scales a collection of features.</p>


```csharp
public void Scale(Layer layer, IEnumerable<long> oids, MapPoint origin, double sx, double sy, double sz)
```
### Scale(Layer, long, MapPoint, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Scales a feature.</p>


```csharp
public void Scale(Layer layer, long oid, MapPoint origin, double sx, double sy)
```
### Scale(Layer, long, MapPoint, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Scales a feature.</p>


```csharp
public void Scale(Layer layer, long oid, MapPoint origin, double sx, double sy, double sz)
```
### Scale(SelectionSet, MapPoint, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Scales a set of features.</p>


```csharp
public void Scale(SelectionSet features, MapPoint origin, double sx, double sy)
```
### Scale(SelectionSet, MapPoint, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Scales a set of features.</p>


```csharp
public void Scale(SelectionSet features, MapPoint origin, double sx, double sy, double sz)
```
### SelectModifiedFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets whether a new selection containing only the modified features will be created by the <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool SelectModifiedFeatures { get; set; }
```
### SelectNewFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets whether a new selection containing only the created features will be created by the <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool SelectNewFeatures { get; set; }
```
### SetOnComitted(Action&lt;bool&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Sets an action that will be called when this EditOperation is committed.</p>


```csharp
public void SetOnComitted(Action<bool> callback)
```
### SetOnComplete(Action)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Sets an action that will be called when this operation is done executing.</p>


```csharp
public void SetOnComplete(Action callback)
```
### SetOnRedone(Action)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Sets an action that will be called when this EditOperation is redone.</p>


```csharp
public void SetOnRedone(Action callback)
```
### SetOnUndone(Action)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Sets an action that will be called when this EditOperation is undone.</p>


```csharp
public void SetOnUndone(Action callback)
```
### SetParcelHistoryCurrent(ParcelLayer, SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Set the history of the selected parcel features to current.</p>


```csharp
public ParcelEditToken SetParcelHistoryCurrent(ParcelLayer parcelLayer, SelectionSet sourceFeatures)
```
### SetParcelHistoryRetired(ParcelLayer, SelectionSet, ParcelRecord)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Set the history of the selected parcel features to retire.</p>


```csharp
public ParcelEditToken SetParcelHistoryRetired(ParcelLayer parcelLayer, SelectionSet sourceFeatures, ParcelRecord parcelRecord)
```
### SetParcelHistoryRetired(ParcelLayer, SelectionSet, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Set the history of the selected parcel features to retire.</p>


```csharp
public ParcelEditToken SetParcelHistoryRetired(ParcelLayer parcelLayer, SelectionSet sourceFeatures, Guid recordGuid)
```
### SetParcelHistoryRetired(ParcelLayer, SelectionSet, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Set the history of the selected parcel features to retire.</p>


```csharp
public ParcelEditToken SetParcelHistoryRetired(ParcelLayer parcelLayer, SelectionSet sourceFeatures, long recordOid)
```
### SetParcelHistoryRetired(ParcelLayer, SelectionSet, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Set the history of the selected parcel features to retire.</p>


```csharp
public ParcelEditToken SetParcelHistoryRetired(ParcelLayer parcelLayer, SelectionSet sourceFeatures, string recordName)
```
### ShowModalMessageAfterFailure

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets a value to show a modal dialog if the EditOperation fails.</p>


```csharp
public bool ShowModalMessageAfterFailure { get; set; }
```
### ShowProgressor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Gets and sets whether to show a progressor during an <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool ShowProgressor { get; set; }
```
### ShrinkParcelsToSeeds(ParcelLayer, SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Shrink selected parcels to seeds.</p>


```csharp
public ParcelEditToken ShrinkParcelsToSeeds(ParcelLayer parcelLayer, SelectionSet sourceFeatures)
```
### Split(Layer, IEnumerable&lt;long&gt;, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Split the given features where the <code class="paramref">splitGeometry</code> intersects.</p>


```csharp
public void Split(Layer layer, IEnumerable<long> oids, Geometry splitGeometry)
```
### Split(Layer, IEnumerable&lt;long&gt;, SplitMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Split features using a specified split method.</p>


```csharp
public void Split(Layer layer, IEnumerable<long> oids, SplitMethod splitMethod)
```
### Split(Layer, IEnumerable&lt;long&gt;, IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Split a number of features at multiple points</p>


```csharp
public void Split(Layer layer, IEnumerable<long> oids, IEnumerable<MapPoint> splitGeometries)
```
### Split(Layer, long, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Split a feature where the <code class="paramref">splitGeometry</code> intersects it.</p>


```csharp
public void Split(Layer layer, long oid, Geometry splitGeometry)
```
### Split(Layer, long, SplitMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Split a feature using a specified split method.</p>


```csharp
public void Split(Layer layer, long oid, SplitMethod splitMethod)
```
### Split(Layer, long, IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Splits a feature at multiple points.</p>


```csharp
public void Split(Layer layer, long oid, IEnumerable<MapPoint> splitGeometries)
```
### Split(SelectionSet, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Splits the lines and polygons in the <code class="paramref">features</code> with the <code class="paramref">splitGeometry</code>.</p>


```csharp
public void Split(SelectionSet features, Geometry splitGeometry)
```
### Split(SelectionSet, SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Splits the lines and polygons in the <code class="paramref">features</code> selection set with the points, lines and polygons in the <code class="paramref">inputFeatures</code> selectionSet.</p>


```csharp
public void Split(SelectionSet features, SelectionSet inputFeatures)
```
### Split(SelectionSet, IEnumerable&lt;Geometry&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Splits the lines and polygons in the <code class="paramref">features</code> with the points, lines and polygons in the <code class="paramref">splitGeometries</code>.</p>


```csharp
public void Split(SelectionSet features, IEnumerable<Geometry> splitGeometries)
```
### TransferAttributes(MapMember, long, MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transfer attributes between two features (or rows) using the stored field mapping.</p>


```csharp
public void TransferAttributes(MapMember source, long sourceOID, MapMember target, long targetOID)
```
### TransferAttributes(MapMember, long, MapMember, long, Dictionary&lt;string, string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transfer attributes between two features (or rows) using the supplied dictionary to map fields.</p>


```csharp
public void TransferAttributes(MapMember source, long sourceOID, MapMember target, long targetOID, Dictionary<string, string> fieldMapping)
```
### TransferAttributes(MapMember, long, MapMember, long, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transfer attributes between two features or rows using the supplied Arcade expression.</p>


```csharp
public void TransferAttributes(MapMember source, long sourceOID, MapMember target, long targetOID, string expression)
```
### TransferParcel(ParcelLayer, ParcelRecord, Layer, long, Layer, List&lt;long&gt;, Layer, List&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transfer parcel from source to target.</p>


```csharp
public ParcelEditToken TransferParcel(ParcelLayer parcelLayer, ParcelRecord parcelRecord, Layer transferParcelLayer, long transferParcelOid, Layer sourceParcelLayer, List<long> sourceParcelOids, Layer targetParcelLayer, List<long> targetParcelOids)
```
### TransferParcel(ParcelLayer, Guid, Layer, long, Layer, List&lt;long&gt;, Layer, List&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transfer parcel from source to target.</p>


```csharp
public ParcelEditToken TransferParcel(ParcelLayer parcelLayer, Guid recordGuid, Layer transferParcelLayer, long transferParcelOid, Layer sourceParcelLayer, List<long> sourceParcelOids, Layer targetParcelLayer, List<long> targetParcelOids)
```
### TransferParcel(ParcelLayer, long, Layer, long, Layer, List&lt;long&gt;, Layer, List&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transfer parcel from source to target.</p>


```csharp
public ParcelEditToken TransferParcel(ParcelLayer parcelLayer, long recordOid, Layer transferParcelLayer, long transferParcelOid, Layer sourceParcelLayer, List<long> sourceParcelOids, Layer targetParcelLayer, List<long> targetParcelOids)
```
### TransferParcel(ParcelLayer, string, Layer, long, Layer, List&lt;long&gt;, Layer, List&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transfer parcel from source to target.</p>


```csharp
public ParcelEditToken TransferParcel(ParcelLayer parcelLayer, string recordName, Layer transferParcelLayer, long transferParcelOid, Layer sourceParcelLayer, List<long> sourceParcelOids, Layer targetParcelLayer, List<long> targetParcelOids)
```
### Transform(Layer, TransformMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transform a layer.</p>


```csharp
public void Transform(Layer layer, TransformMethod transformMethod)
```
### Transform(SelectionSet, TransformMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transform a set of features.</p>


```csharp
public void Transform(SelectionSet features, TransformMethod transformMethod)
```
### Transform(IEnumerable&lt;Layer&gt;, TransformMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Transforms a collection of layers.</p>


```csharp
public void Transform(IEnumerable<Layer> layers, TransformMethod transformMethod)
```
### UndoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Attempts to Undo this EditOperation (only the most recent edit operation can be undone).</p>


```csharp
public Task<bool> UndoAsync()
```
### UpdateAttachment(Table, long, long, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Update an attachment to a row/feature with attachment support.</p>


```csharp
public void UpdateAttachment(Table table, long oid, long attachmentOID, string filePath)
```
### UpdateAttachment(Table, long, long, string, AttachmentProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Update an attachment to a row/feature with attachment support.</p>


```csharp
public void UpdateAttachment(Table table, long oid, long attachmentOID, string filePath, AttachmentProperties properties)
```
### UpdateAttachment(RowHandle, long, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Update an attachment to a row/feature with attachment support.</p>


```csharp
public void UpdateAttachment(RowHandle rowHandle, long attachmentOID, string filePath)
```
### UpdateAttachment(RowHandle, long, string, AttachmentProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Update an attachment to a row/feature with attachment support.</p>


```csharp
public void UpdateAttachment(RowHandle rowHandle, long attachmentOID, string filePath, AttachmentProperties properties)
```
### UpdateAttachment(RowToken, long, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Update an attachment to a row/feature with attachment support.</p>


```csharp
public void UpdateAttachment(RowToken token, long attachmentOID, string filePath)
```
### UpdateAttachment(RowToken, long, string, AttachmentProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Update an attachment to a row/feature with attachment support.</p>


```csharp
public void UpdateAttachment(RowToken token, long attachmentOID, string filePath, AttachmentProperties properties)
```
### UpdateAttachment(MapMember, long, long, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Update an attachment to a row/feature with attachment support.</p>


```csharp
public void UpdateAttachment(MapMember mapMember, long oid, long attachmentOID, string filePath)
```
### UpdateAttachment(MapMember, long, long, string, AttachmentProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">Update an attachment to a row/feature with attachment support.</p>


```csharp
public void UpdateAttachment(MapMember mapMember, long oid, long attachmentOID, string filePath, AttachmentProperties properties)
```


