# ArcGIS.Core.Data.Knowledge

- Type: namespace
- Assembly: ArcGIS.Core.dll




## Members

### DocumentPropertyInfo

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.DocumentPropertyInfo.yml" sourcestartlinenumber="1">Class representing information about the names of the unique identifier document properties in a knowledge graph.
See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.SupportsDocuments" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.DocumentPropertyInfo" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.GetPropertyNameInfo" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraph

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Represents a Knowledge Graph datastore.</p>


### KnowledgeGraphArrayValue

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphArrayValue.yml" sourcestartlinenumber="1">Represents an array of knowledge graph values in a KnowledgeGraph.</p>


### KnowledgeGraphConnectionProperties

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphConnectionProperties.yml" sourcestartlinenumber="1">Represents the properties used to connect to a knowledge graph datastore.</p>


### KnowledgeGraphCursor

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor.yml" sourcestartlinenumber="1">Represents an object returned by a query or text search performed
on a knowledge graph.</p>


### KnowledgeGraphDataModel

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Represents the data model for the knowledge graph.</p>


### KnowledgeGraphEndPoint

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphEndPoint.yml" sourcestartlinenumber="1">Represents an end point for a relationship type in the data model.</p>


### KnowledgeGraphEntityType

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphEntityType.yml" sourcestartlinenumber="1">Represents an entity type in the knowledge graph.</p>


### KnowledgeGraphEntityValue

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphEntityValue.yml" sourcestartlinenumber="1">Represents a knowledge graph entity.</p>


### KnowledgeGraphExtensions

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphExtensions.yml" sourcestartlinenumber="1">Extension methods for use with KnowledgeGraph</p>


### KnowledgeGraphFilterMethod

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphFilterMethod.yml" sourcestartlinenumber="1">Used to define a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet" data-throw-if-not-resolved="false"></xref>.
See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.FromKnowledgeGraph(ArcGIS.Core.Data.Knowledge.KnowledgeGraph%2cArcGIS.Core.Data.Knowledge.KnowledgeGraphFilterMethod)" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphIDSet

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">A collection of named object types and their corresponding list of records to represent a set of rows in a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphIdentifierGeneration

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIdentifierGeneration.yml" sourcestartlinenumber="1">Represents an object containing information about how the knowledge
graph service generates unique identifiers.</p>


### KnowledgeGraphIdentifierInfo

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIdentifierInfo.yml" sourcestartlinenumber="1">Abstract base class representing information about unique identifiers
in the knowledge graph. Concrete subclasses include
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNativeIdentifier" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphUniformIdentifier" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphNamedObjectType

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Abstract base class representing a named object type.
Concrete subclasses include <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphEntityType" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipType" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphNamedObjectTypeRole

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectTypeRole.yml" sourcestartlinenumber="1">Represents the role of a named object type.  See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.GetRole" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphNamedObjectValue

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectValue.yml" sourcestartlinenumber="1">Represents a named object value from a KnowledgeGraph. Named objects can
be either entities or relationships.</p>


### KnowledgeGraphNamedTypeCategory

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="1">Represents the category of a named type.
The default is unspecified. Other options include entity,
relationship, both entity and relationship, and provenance.
Currently used to communicate search targets.</p>
<p></p>
<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="8">The categories supported by the Knowledge Graph is determined by
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.GetSupportedSearchTargets" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphNativeIdentifier

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNativeIdentifier.yml" sourcestartlinenumber="1">Represents a unique identifier information object for a knowledge graph
that uses the database native identifier as the unique identifier for
entities and relationships.</p>


### KnowledgeGraphObjectValue

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphObjectValue.yml" sourcestartlinenumber="1">Represents an anonymous object value in a KnowledgeGraph.</p>


### KnowledgeGraphPathValue

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPathValue.yml" sourcestartlinenumber="1">Represents a path value in a knowledge graph.</p>


### KnowledgeGraphPrimitiveValue

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPrimitiveValue.yml" sourcestartlinenumber="1">Represents a primitive value in a KnowledgeGraph.</p>


### KnowledgeGraphProperty

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty.yml" sourcestartlinenumber="1">Represents a knowledge graph property.</p>


### KnowledgeGraphPropertyInfo

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.yml" sourcestartlinenumber="1">Class representing information about the names of the unique identifier properties in a knowledge graph.
See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.GetPropertyNameInfo" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphPropertyRole

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyRole.yml" sourcestartlinenumber="1">Represents the role of a graph property.  See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty.GetRole" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphProvenanceBehavior

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphProvenanceBehavior.yml" sourcestartlinenumber="1">Indicates whether entities with an entity type of role
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectTypeRole.Provenance" data-throw-if-not-resolved="false"></xref>
should be excluded or included in the query results.  See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.ProvenanceBehavior" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphQueryFilter

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter.yml" sourcestartlinenumber="1">Represents a filter for performing a query against a
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphRelationshipType

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipType.yml" sourcestartlinenumber="1">Represents a relationship type in the knowledge graph.</p>


### KnowledgeGraphRelationshipValue

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipValue.yml" sourcestartlinenumber="1">Represents a knowledge graph relationship.</p>


### KnowledgeGraphRow

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRow.yml" sourcestartlinenumber="1">Represents a row from a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphSearchFilter

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Represents a filter for performing a full text search against a
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphServerError

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphServerError.yml" sourcestartlinenumber="1">Represents an error object returned from a knowledge graph service.</p>


### KnowledgeGraphUUIDMethodHint

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphUUIDMethodHint.yml" sourcestartlinenumber="1">Represents the method that the knowledge graph service uses for generating
unique identifiers in the event that one is not provided by the user.
See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphIdentifierGeneration.GetMethodHint" data-throw-if-not-resolved="false"></xref>.</p>


### KnowledgeGraphUniformIdentifier

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphUniformIdentifier.yml" sourcestartlinenumber="1">Represents a unique identifier information object for a knowledge graph
that uses a uniform property as the unique identifier for entities and
relationships.</p>


### KnowledgeGraphValue

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphValue.yml" sourcestartlinenumber="1">Abstract base class for all kKnowledge graph values.</p>


### KnowledgeGraphValueType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphValueType.yml" sourcestartlinenumber="1">Represents the type of knowledge graph value. See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphValue.KnowledgeGraphValueType" data-throw-if-not-resolved="false"></xref>.</p>


### ProvenancePropertyInfo

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.ProvenancePropertyInfo.yml" sourcestartlinenumber="1">Class representing information about the names of the unique identifier provenance properties in a knowledge graph.
See <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.SupportsProvenance" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphPropertyInfo.ProvenancePropertyInfo" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.GetPropertyNameInfo" data-throw-if-not-resolved="false"></xref>.</p>




