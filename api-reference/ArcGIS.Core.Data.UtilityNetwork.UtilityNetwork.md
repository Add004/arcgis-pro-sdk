# UtilityNetwork

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Represents a utility network.</p>


## Object Signature

```csharp
public sealed class UtilityNetwork : Dataset, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">This class is used to</p>
<ul><li>Create and delete associations</li><li>Update subnetworks</li><li>Update network topology</li><li>Get other utility network classes</li></ul>
<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="5">Objects of this class are obtained by calling <xref href="ArcGIS.Core.Data.Geodatabase.OpenDataset%60%601(System.String)" data-throw-if-not-resolved="false"></xref></p>


## Members

### AddAssociation(Association)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Adds an association between two rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddAssociation(Association association)
```
### AreServerCapabilitiesSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets whether or not the utility network supports server capabilities.</p>


```csharp
public bool AreServerCapabilitiesSupported()
```
### CreateElement(Row)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Creates an <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> object, which represents a Row (or Row + Terminal) in a utility network.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Element CreateElement(Row row)
```
### CreateElement(Row, Terminal)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Creates an <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> object, which represents a Row (or Row + Terminal) in a utility network.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Element CreateElement(Row row, Terminal terminal)
```
### CreateElement(AssetType, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Creates an <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> object, which represents a Row (or Row + Terminal) in a utility network.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Element CreateElement(AssetType assetType, Guid globalID)
```
### CreateElement(AssetType, Guid, Terminal)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Creates an <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> object, which represents a Row (or Row + Terminal) in a utility network.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Element CreateElement(AssetType assetType, Guid globalID, Terminal terminal)
```
### DeleteAssociation(Association)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Deletes an association between two rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteAssociation(Association association)
```
### GetAssociationFeatures(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Returns a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationFeature" data-throw-if-not-resolved="false"></xref>s that represent the associations that exist between features within the given extent.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<AssociationFeature> GetAssociationFeatures(Envelope extent)
```
### GetAssociationFeatures(Envelope, AssociationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Returns a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationFeature" data-throw-if-not-resolved="false"></xref>s that represent the associations that exist between features within the given extent, of the specified <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<AssociationFeature> GetAssociationFeatures(Envelope extent, AssociationType associationType)
```
### GetAssociations(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Returns a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.Association" data-throw-if-not-resolved="false"></xref> objects present in the geodatabase for a given row.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public IReadOnlyList<Association> GetAssociations(Element element)
```
### GetAssociations(Element, AssociationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Returns a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.Association" data-throw-if-not-resolved="false"></xref> objects of type <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType" data-throw-if-not-resolved="false"></xref>
present in the geodatabase for a given row.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public IReadOnlyList<Association> GetAssociations(Element element, AssociationType associationType)
```
### GetCircuitManager(TelecomDomainNetwork)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager" data-throw-if-not-resolved="false"></xref> object used to manipulate circuits.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitManager GetCircuitManager(TelecomDomainNetwork telecomDomainNetwork)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition" data-throw-if-not-resolved="false"></xref> object that describes this utility network.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public UtilityNetworkDefinition GetDefinition()
```
### GetDiagramManager()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets the associated/contained <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramManager" data-throw-if-not-resolved="false"></xref> of the network.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public DiagramManager GetDiagramManager()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in the <xref href="ArcGIS.Core.Data.UtilityNetwork" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetFeaturesForElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets a list of ObjectID based <xref href="ArcGIS.Core.Data.Selection" data-throw-if-not-resolved="false"></xref> for corresponding input <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> objects.</p>


```csharp
public IReadOnlyList<Selection> GetFeaturesForElements(IEnumerable<Element> elements)
```
### GetServerCapabilities()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets the supported server capabilities of the utility network.</p>


```csharp
public UtilityNetworkServerCapabilities GetServerCapabilities()
```
### GetState()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkState" data-throw-if-not-resolved="false"></xref> representing the current state of the utility network.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public UtilityNetworkState GetState()
```
### GetSubnetworkManager()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager" data-throw-if-not-resolved="false"></xref> object that can be used to query and edit subnetworks.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SubnetworkManager GetSubnetworkManager()
```
### GetSystemTable(SystemTableType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Opens the specified utility network system table.</p>


```csharp
public Table GetSystemTable(SystemTableType systemTableType)
```
### GetTable(NetworkSource)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Returns the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> that corresponds to a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkSource" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public Table GetTable(NetworkSource networkSource)
```
### GetTraceManager()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.TraceManager" data-throw-if-not-resolved="false"></xref> object used to perform traces.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public TraceManager GetTraceManager()
```
### GetUnitIdentifierManager()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets a UnitIdentifierManager object that can be used to work with unit identifiers.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public UnitIdentifierManager GetUnitIdentifierManager()
```
### HasTelecomNetwork

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets whether the utility network has a telecom domain network.</p>


```csharp
public bool HasTelecomNetwork { get; }
```
### IsSystemTableSupported(SystemTableType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets a value indicating whether the system table specified by <code class="paramref">systemTableType</code> is supported
by the current <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetSchemaVersion" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsSystemTableSupported(SystemTableType systemTableType)
```
### TraverseAssociations(IEnumerable&lt;Element&gt;, TraverseAssociationsDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Provides a mechanism to return all <xref href="ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsResult" data-throw-if-not-resolved="false"></xref> objects beginning at a list of starting elements and following a specified traversal.</p>


```csharp
public TraverseAssociationsResult TraverseAssociations(IEnumerable<Element> startElements, TraverseAssociationsDescription traverseAssociationsDescription)
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this derived dataset.</p>


```csharp
public override DatasetType Type { get; }
```
### ValidateNetworkTopology()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Validates the entire utility network topology.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ValidationResult ValidateNetworkTopology()
```
### ValidateNetworkTopology(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Validates the utility network topology within the provided extent.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ValidationResult ValidateNetworkTopology(Geometry extent)
```
### ValidateNetworkTopology(Geometry, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Validates the utility network topology within the provided extent.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ValidationResult ValidateNetworkTopology(Geometry extent, ServiceSynchronizationType serviceSynchronizationType)
```
### ValidateNetworkTopology(Geometry, ServiceSynchronizationType, ValidationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Validates the utility network topology within the provided extent according to the provided validation type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ValidationResult ValidateNetworkTopology(Geometry extent, ServiceSynchronizationType serviceSynchronizationType, ValidationType validationType)
```
### ValidateNetworkTopology(IEnumerable&lt;Selection&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Validates the utility network topology within the provided extent according to the provided validation type and selection set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ValidationResult ValidateNetworkTopology(IEnumerable<Selection> selections)
```
### ValidateNetworkTopology(IEnumerable&lt;Selection&gt;, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Validates the utility network topology within the provided extent according to the provided validation type and selection set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ValidationResult ValidateNetworkTopology(IEnumerable<Selection> selections, ServiceSynchronizationType serviceSynchronizationType)
```
### ValidateNetworkTopology(IEnumerable&lt;Selection&gt;, ServiceSynchronizationType, ValidationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.yml" sourcestartlinenumber="1">Validates the utility network topology within the provided extent according to the provided validation type and selection set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ValidationResult ValidateNetworkTopology(IEnumerable<Selection> selections, ServiceSynchronizationType serviceSynchronizationType, ValidationType validationType)
```


