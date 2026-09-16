# ArcGIS.Desktop.Editing

- Type: namespace
- Assembly: ArcGIS.Desktop.Editing.dll




## Members

### AnnotationProperties

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Provides access to the attributes of annotation features.</p>


### AssociationDescription

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Represents a connectivity (spatial and non-spatial), containment, or structural attachment association in a utility network.</p>


### AttachmentProperties

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">Attachments may include properties to provide additional
information about the attachment.  The properties of this class
describe the properties that may be stored.</p>
<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="5">However, not all attachment tables support all properties.
Attempting to set a property where it is not currently supported
is not considered an error.  That property is silently ignored.</p>


### BaseRelationshipDescription

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.BaseRelationshipDescription.yml" sourcestartlinenumber="1">Base class for representing a relationship between two rows.  See <xref href="ArcGIS.Desktop.Editing.RelationshipDescription" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription" data-throw-if-not-resolved="false"></xref>.</p>


### ClipMode

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.ClipMode.yml" sourcestartlinenumber="1">Describes options on how to clip features.</p>


### DimensionProperties

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.DimensionProperties.yml" sourcestartlinenumber="1">Provides access to the attributes of dimension features.</p>


### EditOperation

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.yml" sourcestartlinenumber="1">EditOperations are shortlived objects for performing an Edit, they are generally immediately filled with the parameters of the desired edit and executed then
they are discarded after the editor executes them...</p>


### EditOperation.IEditContext

- Kind: interface

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.IEditContext.yml" sourcestartlinenumber="1">Interface of the context given to an edit callback to invalidate features within an edit.</p>


### EditOperationType

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperationType.yml" sourcestartlinenumber="1">Describes the mode of the EditOperation.</p>


### EditType

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.EditType.yml" sourcestartlinenumber="1">Describes different types of edits being performed, inserting a new row, updating an existing row or deleting an existing row.</p>


### ElevationCaptureMode

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCaptureMode.yml" sourcestartlinenumber="1">Defines modes for capturing Elevation when an edit is performed.</p>


### ElevationCapturing

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Manages Elevation capture settings for Editing workflows.</p>


### ExecuteModeType

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.ExecuteModeType.yml" sourcestartlinenumber="1">An enumeration of possible execute mode types. Used in an <xref href="ArcGIS.Desktop.Editing.EditOperation" data-throw-if-not-resolved="false"></xref> to control the order of edit function execution.</p>


### ExifData

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ExifData.yml" sourcestartlinenumber="1">ExifData captures supported Exchangeable Image File (EXIF) data.</p>


### ExifData.ExifIFD0

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ExifData.ExifIFD0.yml" sourcestartlinenumber="1">ExifIFD0 captures supported EXIF Image File Directory (IFD) tags
from the 0th IFD.</p>


### ExifData.ExifSubIFD

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ExifData.ExifSubIFD.yml" sourcestartlinenumber="1">ExifSubIFD captures supported EXIF Image File Directory (IFD) sub tags.</p>


### GeodatabaseTopologyProperties

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.GeodatabaseTopologyProperties.yml" sourcestartlinenumber="1">A class representing a geodatabase topology.</p>


### GroundToGridCorrection

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Provides helper and extension methods for accessing and setting ground to grid corrections.</p>


### InspectorProvider

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Provides a mechanism to customize attribute behavior within an inspector.</p>


### KnowledgeGraphDocumentDescription

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphDocumentDescription.yml" sourcestartlinenumber="1">Represents a document row in a knowledge graph.</p>


### KnowledgeGraphProvenanceDescription

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.yml" sourcestartlinenumber="1">Represents the information in a knowledge graph provenance row.</p>


### KnowledgeGraphRelationshipDescription

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription.yml" sourcestartlinenumber="1">Represents a relationship between two entities in a knowledge graph.</p>


### KnowledgeGraphSourceType

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.KnowledgeGraphSourceType.yml" sourcestartlinenumber="1">Defines the source of information stored in a property of an entity or relationship.  <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphProvenanceDescription.SourceType" data-throw-if-not-resolved="false"></xref>.</p>


### MapTopologyProperties

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.MapTopologyProperties.yml" sourcestartlinenumber="1">A class representing a map topology.</p>


### NoTopologyProperties

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.NoTopologyProperties.yml" sourcestartlinenumber="1">A class representing the &quot;No Topology&quot; option.</p>


### ParallelOffset

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Defines the parameters used to create a parallel offset from line features.</p>


### ParallelOffset.Builder

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Defines the parameters used to create a parallel offset from line features.</p>


### ParallelOffset.CornerType

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.CornerType.yml" sourcestartlinenumber="1">Specifies the shape of the corners created In the copied lines.</p>


### ParallelOffset.SideType

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.SideType.yml" sourcestartlinenumber="1">Specifies the side to create a parallel offset.</p>


### ParcelEdge

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdge.yml" sourcestartlinenumber="1">ParcelEdge represents a set of line properties that define how it is related to a parcel edge.</p>


### ParcelEdgeCollection

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdgeCollection.yml" sourcestartlinenumber="1">ParcelEdgeCollection represents a collection of parcel edges in a clockwise order.</p>


### ParcelEditToken

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEditToken.yml" sourcestartlinenumber="1">A ParcelEditToken represents a collection of parcel feature edits; the edits will occur after the edit operation has completed.</p>


### ParcelFeatures

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelFeatures.yml" sourcestartlinenumber="1">Represents basic information about a parcel feature.</p>


### ParcelLineInfo

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">The ParcelLineInfo class represents a set of line properties that define how it is related to a parcel edge.</p>


### ParcelLineToEdgeRelationship

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineToEdgeRelationship.yml" sourcestartlinenumber="1">The enumeration for describing a boundary line’s start and end points in
relation to its parcel edge.</p>


### ParcelRecord

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelRecord.yml" sourcestartlinenumber="1">The ParcelRecord class provides basic information about a parcel record.</p>


### ReadOnlyToolOptions

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">A read-only wrapper for <xref href="ArcGIS.Desktop.Editing.ToolOptions" data-throw-if-not-resolved="false"></xref> made available by <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate.GetToolOptions(System.String)" data-throw-if-not-resolved="false"></xref></p>


### RelationshipDescription

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.RelationshipDescription.yml" sourcestartlinenumber="1">Represents a relationship between two rows.</p>


### RowHandle

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">A RowHandle represents a common structure for the many ways to reference a row.</p>


### RowToken

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.RowToken.yml" sourcestartlinenumber="1">A RowToken represents a feature that will be created but has not yet been created. It can be used in place of the object ID in referencing that feature even before it has an Object ID.</p>


### RubbersheetByGeometries

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByGeometries.yml" sourcestartlinenumber="1">Perform a rubbersheet operation using the specified geometries.</p>


### RubbersheetByLayers

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByLayers.yml" sourcestartlinenumber="1">Perform a rubbersheet operation using geometries from specified layers.</p>


### RubbersheetMethod

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetMethod.yml" sourcestartlinenumber="1">A base class used to represent a rubbersheet method.
For use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Rubbersheet(ArcGIS.Desktop.Mapping.Layer%2cArcGIS.Desktop.Editing.RubbersheetMethod)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.EditOperation.Rubbersheet(ArcGIS.Desktop.Mapping.SelectionSet%2cArcGIS.Desktop.Editing.RubbersheetMethod)" data-throw-if-not-resolved="false"></xref>.
Possible transformation methods include <xref href="ArcGIS.Desktop.Editing.RubbersheetByLayers" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.RubbersheetByGeometries" data-throw-if-not-resolved="false"></xref>.</p>


### RubbersheetMethodType

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetMethodType.yml" sourcestartlinenumber="1">An enumeration of possible rubbersheet methods.</p>


### SequencedEdgeParcelParams

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.SequencedEdgeParcelParams.yml" sourcestartlinenumber="1">The sequenced edge parcel params that define the behavior of GetSequencedParcelEdgeInfoAsync.</p>


### SplitByDistance

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByDistance.yml" sourcestartlinenumber="1">Split By Distance class.  Use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref></p>


### SplitByEqualDistance

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByEqualDistance.yml" sourcestartlinenumber="1">Split By Equal Distance class.  Use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref></p>


### SplitByEqualParts

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByEqualParts.yml" sourcestartlinenumber="1">Split By Equal Parts class.  Use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref></p>


### SplitByGeometry

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByGeometry.yml" sourcestartlinenumber="1">Split By Geometry class.  Use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref></p>


### SplitByPercentage

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByPercentage.yml" sourcestartlinenumber="1">Split By Percentage class.  Use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref></p>


### SplitByVaryingDistance

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByVaryingDistance.yml" sourcestartlinenumber="1">Split By Varying Distance class.  Use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref></p>


### SplitMethod

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitMethod.yml" sourcestartlinenumber="1">A base split method class.  For use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref>.<br>
Different split methods are <xref href="ArcGIS.Desktop.Editing.SplitByGeometry" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Editing.SplitByPercentage" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Editing.SplitByEqualParts" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Editing.SplitByDistance" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Editing.SplitByEqualDistance" data-throw-if-not-resolved="false"></xref>, and <xref href="ArcGIS.Desktop.Editing.SplitByVaryingDistance" data-throw-if-not-resolved="false"></xref></p>


### ToolOptions

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Property collection that may be serialized to the CIM as a Template Tool's Options</p>


### ToolOptionsEmbeddableControl

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">helper class for constructing an <xref href="ArcGIS.Desktop.Framework.Controls.EmbeddableControl" data-throw-if-not-resolved="false"></xref> to be used with <xref href="ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.ToolOptions" data-throw-if-not-resolved="false"></xref></p>


### TopologyProperties

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.TopologyProperties.yml" sourcestartlinenumber="1">Represents a base set of properties to define a topology option.  See <xref href="ArcGIS.Desktop.Editing.GeodatabaseTopologyProperties" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Editing.MapTopologyProperties" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Editing.NoTopologyProperties" data-throw-if-not-resolved="false"></xref>.</p>


### TransformByLinkLayer

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformByLinkLayer.yml" sourcestartlinenumber="1">Transform using a <xref href="ArcGIS.Desktop.Mapping.Layer" data-throw-if-not-resolved="false"></xref> containing link features.</p>


### TransformByLinkLines

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformByLinkLines.yml" sourcestartlinenumber="1">Transform using a collection of <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> geometries as links.</p>


### TransformMethod

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformMethod.yml" sourcestartlinenumber="1">A base class used to represent a transformation method.
For use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Transform(ArcGIS.Desktop.Mapping.Layer%2cArcGIS.Desktop.Editing.TransformMethod)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.EditOperation.Transform(ArcGIS.Desktop.Mapping.SelectionSet%2cArcGIS.Desktop.Editing.TransformMethod)" data-throw-if-not-resolved="false"></xref>.
Possible transformation methods include <xref href="ArcGIS.Desktop.Editing.TransformByLinkLayer" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.TransformByLinkLines" data-throw-if-not-resolved="false"></xref>.</p>


### TransformMethodType

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformMethodType.yml" sourcestartlinenumber="1">An enumeration of possible transformation types.</p>




