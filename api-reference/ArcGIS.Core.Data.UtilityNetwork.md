# ArcGIS.Core.Data.UtilityNetwork

- Type: namespace
- Assembly: ArcGIS.Core.dll




## Members

### AssetGroup

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetGroup.yml" sourcestartlinenumber="1">The AssetGroup class provides information about Asset Groups within the utility network.  In the core geodatabase, they are implemented as subtypes.</p>


### AssetType

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets information about the definition of an Asset Type.</p>


### Association

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Represents a connectivity (spatial and non-spatial), containment, or structural attachment association.</p>


### AssociationDeleteType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationDeleteType.yml" sourcestartlinenumber="1">Determines the behavior that occurs when attempting to delete a feature which has containment or structural attachment associations to other features.</p>


### AssociationFeature

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationFeature.yml" sourcestartlinenumber="1">Represents a connectivity, containment, or structural attachment association, including a <xref href="ArcGIS.Core.Geometry.Geometry" data-throw-if-not-resolved="false"></xref> representing a connection between the two rows involved in the association.</p>


### AssociationRoleType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationRoleType.yml" sourcestartlinenumber="1">Specifies whether a particular <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> can be a container, structure, or neither.</p>


### AssociationType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationType.yml" sourcestartlinenumber="1">Describes a type of association</p>


### ConfigurationPath

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ConfigurationPath.yml" sourcestartlinenumber="1">The configuration path class details the set of flow paths between <xref href="ArcGIS.Core.Data.UtilityNetwork.Terminal" data-throw-if-not-resolved="false"></xref>s for a given device configuration.</p>


### ConnectivityPolicy

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ConnectivityPolicy.yml" sourcestartlinenumber="1">Specifies the connectivity policy for edges in the network.</p>


### ContainerSplitPolicy

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ContainerSplitPolicy.yml" sourcestartlinenumber="1">Specifies whether the contents of a container are split when the container is split.</p>


### ContainmentVisibility

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ContainmentVisibility.yml" sourcestartlinenumber="1">Specifies the visibility of a content in a <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Containment" data-throw-if-not-resolved="false"></xref> association.</p>


### Directionality

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Directionality.yml" sourcestartlinenumber="1">Specifies the directionality setting of terminals on a device.</p>


### DomainNetwork

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">The DomainNetwork class is used to represent a domain network inside a utility network.  A domain network typically represents an industry
domain such as 'Electric Distribution', 'Gas', or 'Water.'
DomainNetwork objects can be obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetDomainNetworks" data-throw-if-not-resolved="false"></xref>.</p>


### EditMode

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.EditMode.yml" sourcestartlinenumber="1">The editing mode used when updating subnetworks.</p>


### Element

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Represents a row inside a utility network.</p>


### ExportOptions

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ExportOptions.yml" sourcestartlinenumber="1">Represents a mechanism to perform an export operation.</p>


### NetworkAttribute

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">The NetworkAttribute class is used to represent a network attribute inside a utility network.  Network attributes correspond to weights in the geometric network.
NetworkAttribute objects can be obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetNetworkAttributes" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetNetworkAttribute(System.String)" data-throw-if-not-resolved="false"></xref></p>


### NetworkAttributeAssignment

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttributeAssignment.yml" sourcestartlinenumber="1">Describes an assignment of a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> to a particular <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> of a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkSource" data-throw-if-not-resolved="false"></xref>.</p>


### NetworkAttributeDataType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttributeDataType.yml" sourcestartlinenumber="1">Specifies the data type of the network attribute.</p>


### NetworkSource

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Represents a network source in a utility network.</p>


### Rule

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Rule.yml" sourcestartlinenumber="1">Represents a rule in the utility network.  These define how features can be associated with each other through connectivity, containment, and attachment.</p>


### RuleElement

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.RuleElement.yml" sourcestartlinenumber="1">Represents an element of a utility network rule.  Each element represents one participant in an association.</p>


### RuleType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.RuleType.yml" sourcestartlinenumber="1">Specifies the type of utility network rule.</p>


### SourceType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SourceType.yml" sourcestartlinenumber="1">Specifies the type of network source.</p>


### SourceUsageType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SourceUsageType.yml" sourcestartlinenumber="1">Specifies the type of rows stored in each utility network table</p>


### Subnetwork

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Subnetwork.yml" sourcestartlinenumber="1">Represents a subnetwork (circuit, zone) in a utility network</p>


### SubnetworkController

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.yml" sourcestartlinenumber="1">Represents subnetwork controller.</p>


### SubnetworkControllerType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkControllerType.yml" sourcestartlinenumber="1">Specifies the category of subnetwork controllers that are supported by a domain network.</p>


### SubnetworkExportOptions

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Represents a mechanism to export a <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref>.</p>


### SubnetworkExportResultType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportResultType.yml" sourcestartlinenumber="1">Specifies the result of exporting a <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref>.</p>


### SubnetworkManager

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.yml" sourcestartlinenumber="1">The SubnetworkManager is a class that contains a collection of subnetwork management routines.</p>


### SubnetworkStates

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">Allowable states for subnetworks.</p>


### SubnetworkUpdateOptions

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkUpdateOptions.yml" sourcestartlinenumber="1">Represents a mechanism to update a <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref>.</p>


### SystemTableType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SystemTableType.yml" sourcestartlinenumber="1">Specifies a utility network system table.</p>


### Terminal

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Represents a single terminal on a junction feature.</p>


### TerminalConfiguration

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Represents a configuration of <xref href="ArcGIS.Core.Data.UtilityNetwork.Terminal" data-throw-if-not-resolved="false"></xref> objects that are assigned to zero or more AssetTypes.</p>


### TerminalPath

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalPath.yml" sourcestartlinenumber="1">A value object that specifies a flow path between two <xref href="ArcGIS.Core.Data.UtilityNetwork.Terminal" data-throw-if-not-resolved="false"></xref>s.</p>


### Tier

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Tiers demarcate a logical level within a network.  E.g., in an electric distribution network, there may be Subtransmission, MediumVoltage and LowVoltage tiers.</p>


### TierDefinition

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierDefinition.yml" sourcestartlinenumber="1">Returns the type of subnetworks suported in this domain network.</p>


### TierGroup

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierGroup.yml" sourcestartlinenumber="1">Tier groups provide an extra level of organization for tiers.</p>
<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierGroup.yml" sourcestartlinenumber="3">For example, a gas network may be divided into two tier groups - Transmission and Distribution.
Each of these tier groups would contain a set of tiers specific to that group.  For example, Distribution Pressure and Distribution Isolation might be tiers within the
Distribution tier group.</p>


### TierTopologyType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierTopologyType.yml" sourcestartlinenumber="1">Specifies the type of topology that makes up a <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier" data-throw-if-not-resolved="false"></xref> definition</p>


### TraversalDirection

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraversalDirection.yml" sourcestartlinenumber="1">The traversal direction for a Traverse Associations operation.</p>


### TraverseAssociationsDescription

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsDescription.yml" sourcestartlinenumber="1">Represents a mechanism to return <xref href="ArcGIS.Core.Data.UtilityNetwork.Association" data-throw-if-not-resolved="false"></xref> objects in a specified <xref href="ArcGIS.Core.Data.UtilityNetwork.TraversalDirection" data-throw-if-not-resolved="false"></xref>.</p>


### TraverseAssociationsResult

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsResult.yml" sourcestartlinenumber="1">Represents a collection of <xref href="ArcGIS.Core.Data.UtilityNetwork.Association" data-throw-if-not-resolved="false"></xref>s and the mapping between involved <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref>s and their field name-values from an associations traversal operation.</p>


### UpdateSubnetworkPolicy

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UpdateSubnetworkPolicy.yml" sourcestartlinenumber="1">Describes how subnetwork names are promulgated to associated features.</p>


### UtilityNetwork

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Represents a utility network.</p>


### UtilityNetworkDefinition

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a utility network.</p>


### UtilityNetworkExtensions

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">This convenience API provides commonly-used UtilityNetwork-related extension methods for the <i>ArcGIS.Core.Data.UtilityNetwork</i> API.</p>


### UtilityNetworkServerCapabilities

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkServerCapabilities.yml" sourcestartlinenumber="1">Represents the set of supported capabilities of a <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork" data-throw-if-not-resolved="false"></xref> in a feature service connection.</p>


### UtilityNetworkState

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkState.yml" sourcestartlinenumber="1">Provides information about the current state of the utility network</p>


### ValidationResult

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationResult.yml" sourcestartlinenumber="1">Provides information about the results of a call to <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.ValidateNetworkTopology" data-throw-if-not-resolved="false"></xref>.</p>


### ValidationType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationType.yml" sourcestartlinenumber="1">Specifies the type of validation performed when validating a utility network.</p>


### VersionSpecification

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.VersionSpecification.yml" sourcestartlinenumber="1">Specifies a type of version.</p>




