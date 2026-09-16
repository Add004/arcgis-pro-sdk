# CoreDataExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">This convenience API provides commonly-used geodatabase extension methods for the <i>ArcGIS.Core.Data</i> API.</p>


## Object Signature

```csharp
public static class CoreDataExtensions
```


## Members

### AddActivationExtension(Table, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Registers an extension id (guid) with the specified table. This method
must be called on the Main CIM Thread. Use QueuedTask.Run.</p>


```csharp
public static void AddActivationExtension(this Table table, Guid extensionId)
```
### AlterInEditOperation(CircuitManager, Circuit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Updates a circuit row in the circuit table with the provided argument's values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void AlterInEditOperation(this CircuitManager circuitManager, Circuit circuit)
```
### CreateInEditOperation(CircuitManager, Circuit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Inserts a circuit row in the circuit table with the provided argument's values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void CreateInEditOperation(this CircuitManager circuitManager, Circuit circuit)
```
### DeleteInEditOperation(CircuitManager, IReadOnlyList&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Mark the given circuits as deleted.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void DeleteInEditOperation(this CircuitManager circuitManager, IReadOnlyList<string> circuitNames)
```
### EvaluateInEditOperation(AttributeRuleManager, AttributeRuleEvaluationDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Evaluates all the applicable tables and feature classes in the geodatabase associated with <code class="paramref">attributeRuleManager</code>
using the operation(s) specified by <code class="paramref">description</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static AttributeRuleEvaluationResult EvaluateInEditOperation(this AttributeRuleManager attributeRuleManager, AttributeRuleEvaluationDescription description)
```
### GetActivationExtensions(Table)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Gets the readonly list of extension ids (guids) registered with the table.
This method must be called on the Main CIM Thread. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<Guid> GetActivationExtensions(this Table table)
```
### GetDataConnection(Dataset)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Gets the CIMDataConnection for the specified dataset. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static CIMDataConnection GetDataConnection(this Dataset dataset)
```
### GetDataConnections(IEnumerable&lt;Dataset&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Gets the CIMDataConnections for the specified datasets. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<CIMDataConnection> GetDataConnections(this IEnumerable<Dataset> datasets)
```
### GetHasActivationExtension(Table, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Gets if the specified extension id (guid) is registered with the table. This method
must be called on the Main CIM Thread. Use QueuedTask.Run.</p>


```csharp
public static bool GetHasActivationExtension(this Table table, Guid extensionId)
```
### MarkAsExceptionInEditOperation(Topology, TopologyError)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Marks the topology error specified by <code class="paramref">topologyError</code> as an exception.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void MarkAsExceptionInEditOperation(this Topology topology, TopologyError topologyError)
```
### PartialPostInEditOperation(Version, PartialPostOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Partial posts this version against a target version specified in <code class="paramref">partialPostOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static PartialPostResult PartialPostInEditOperation(this Version version, PartialPostOptions partialPostOptions)
```
### PostInEditOperation(Version, PostOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Posts this version against a target version specified in <code class="paramref">postOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void PostInEditOperation(this Version version, PostOptions postOptions)
```
### ReconcileInEditOperation(Version, ReconcileOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Reconciles this version against a target version specified in <code class="paramref">reconcileOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ReconcileResult ReconcileInEditOperation(this Version version, ReconcileOptions reconcileOptions)
```
### ReconcileInEditOperation(Version, ReconcileOptions, PartialPostOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Reconciles and partial posts this version against a target version specified in <code class="paramref">reconcileOptions</code> and <code class="paramref">partialPostOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ReconcileResult ReconcileInEditOperation(this Version version, ReconcileOptions reconcileOptions, PartialPostOptions partialPostOptions)
```
### ReconcileInEditOperation(Version, ReconcileOptions, PostOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Reconciles and posts this version against a target version specified in <code class="paramref">reconcileOptions</code> and <code class="paramref">postOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ReconcileResult ReconcileInEditOperation(this Version version, ReconcileOptions reconcileOptions, PostOptions postOptions)
```
### RefreshDatastore(Version)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Refreshes the version and layers in all maps that references this version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void RefreshDatastore(this Version version)
```
### RemoveActivationExtension(Table, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Removes the extension id (guid) from being registered with the table. This method
must be called on the Main CIM Thread. Use QueuedTask.Run.</p>


```csharp
public static void RemoveActivationExtension(this Table table, Guid extensionId)
```
### ReserveUnitIDsInEditOperation(UnitIdentifierManager, UnitIdentifier, short, short)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Reserves a range to create a gap in the unit range <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange" data-throw-if-not-resolved="false"></xref> space of an equipment container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void ReserveUnitIDsInEditOperation(this UnitIdentifierManager unitIdentifierManager, UnitIdentifier container, short firstUnit, short lastUnit)
```
### ResetInEditOperation(UnitIdentifierManager, IEnumerable&lt;UnitIdentifier&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Removes gaps and resets the unit space to be contiguous within an equipment hierarchy.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void ResetInEditOperation(this UnitIdentifierManager unitIdentifierManager, IEnumerable<UnitIdentifier> containers)
```
### ResizeInEditOperation(UnitIdentifierManager, UnitIdentifier, short)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Updates the number of units in an equipment container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void ResizeInEditOperation(this UnitIdentifierManager unitIdentifierManager, UnitIdentifier content, short lastUnit)
```
### UnmarkAsExceptionInEditOperation(Topology, TopologyError)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Resets the <code class="paramref">topologyError</code> currently marked as an exception to once again be an error.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void UnmarkAsExceptionInEditOperation(this Topology topology, TopologyError topologyError)
```
### UpdateErrorsInEditOperation(AttributeRuleManager, IEnumerable&lt;AttributeRuleError&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Updates the validation error system tables specified by <code class="paramref">validationErrors</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void UpdateErrorsInEditOperation(this AttributeRuleManager attributeRuleManager, IEnumerable<AttributeRuleError> validationErrors)
```
### ValidateInEditOperation(Topology, ValidationDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Ensures data integrity by validating the features in a topology in the area specified by
<xref href="ArcGIS.Core.Data.Topology.ValidationDescription.Extent" data-throw-if-not-resolved="false"></xref> against a pre-defined set of topology rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ValidationResult ValidateInEditOperation(this Topology topology, ValidationDescription validationDescription)
```
### VerifyInEditOperation(CircuitManager, IReadOnlyList&lt;string&gt;, CircuitVerifyOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CoreDataExtensions.yml" sourcestartlinenumber="1">Updates the status of a list of circuits.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<CircuitVerifyResult> VerifyInEditOperation(this CircuitManager circuitManager, IReadOnlyList<string> circuitNames, CircuitVerifyOptions circuitVerifyOptions)
```


