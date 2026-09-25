# ArcGIS.Core.Data.Topology

- Type: namespace
- Assembly: ArcGIS.Core.dll




## Members

### ErrorDescription

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.ErrorDescription.yml" sourcestartlinenumber="1">Represents a mechanism to retrieve <xref href="ArcGIS.Core.Data.Topology.TopologyError" data-throw-if-not-resolved="false"></xref> associated with a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


### ErrorType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Topology.ErrorType.yml" sourcestartlinenumber="1">Specifies the type of topology error to be retrieved.</p>


### FeatureInfo

- Kind: class

<p>
    Represents the parent feature of a topological element.
    </p>
<p>
    A <i>parent feature</i> refers to a feature in the feature space from which one or more topological elements are
    created in the topology graph space.
    </p>


### Topology

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Represents a topology dataset.</p>


### TopologyDefinition

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


### TopologyEdge

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Represents a topological edge within a topology graph.</p>


### TopologyElement

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Represents a topological element within a topology graph.</p>


### TopologyError

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Represents an error associated with a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


### TopologyGraph

- Kind: class

<p>
    Represents an in-memory representation of the topologically-integrated features within the current topology.
    </p>
<p>
    When a topology graph is built via <xref href="ArcGIS.Core.Data.Topology.Topology.BuildGraph(ArcGIS.Core.Geometry.Geometry%2cSystem.Action%7bArcGIS.Core.Data.Topology.TopologyGraph%7d)" data-throw-if-not-resolved="false"></xref>, spatial relationships between features
    are discovered, analyzed and established to form an in-memory graph of topological elements. These topological
    elements consist of <xref href="ArcGIS.Core.Data.Topology.TopologyNode" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.Topology.TopologyEdge" data-throw-if-not-resolved="false"></xref>, which correspond to points and
    lines, respectively, in the feature space.
    </p>
<p>
    A <i>parent feature</i> refers to a feature in the feature space from which one or more topological elements are
    created in the topology graph space.
    </p>


### TopologyNode

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyNode.yml" sourcestartlinenumber="1">Represents a topological node within a topology graph.</p>


### TopologyRule

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRule.yml" sourcestartlinenumber="1">Represents a rule that has been defined for a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


### TopologyRuleType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">Specifies the types of topology rules.</p>


### TopologyState

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyState.yml" sourcestartlinenumber="1">Specifies the state of the topology.</p>


### ValidationDescription

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.ValidationDescription.yml" sourcestartlinenumber="1">Represents a mechanism to validate a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


### ValidationResult

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.Topology.ValidationResult.yml" sourcestartlinenumber="1">Provides information about the results of a call to <xref href="ArcGIS.Core.Data.Topology.Topology.Validate(ArcGIS.Core.Data.Topology.ValidationDescription)" data-throw-if-not-resolved="false"></xref>.</p>




