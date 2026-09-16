# CircuitManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Provides methods to query, create, update, delete, verify, and export circuits in a telecom domain network.</p>


## Object Signature

```csharp
public sealed class CircuitManager : CoreObjectsBase, IDisposable
```


## Members

### Alter(Circuit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Updates a circuit row in the circuit table with the provided argument's values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Alter(Circuit circuit)
```
### Create(Circuit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Inserts a circuit row in the circuit table with the provided argument's values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Create(Circuit circuit)
```
### Delete(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Marks the specified circuits as deleted.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Delete(IEnumerable<string> circuitNames)
```
### Export(IEnumerable&lt;string&gt;, CircuitExportOptions, Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Exports a list of circuits.</p>


```csharp
public void Export(IEnumerable<string> circuitNames, CircuitExportOptions circuitExportOptions, Uri outputFolderPath)
```
### GetCircuitNames(CircuitFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Gets the names of the circuits in relation to the provided filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetCircuitNames(CircuitFilter circuitFilter)
```
### GetCircuitSectionUserFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Gets the list of user fields from the circuit section table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetCircuitSectionUserFields()
```
### GetCircuitUserFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Gets the list of user fields from the circuit table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetCircuitUserFields()
```
### GetCircuits(CircuitFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Gets the circuits in relation to the provided filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Circuit> GetCircuits(CircuitFilter circuitFilter)
```
### GetSubcircuitUserFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Gets the list of user fields from the subcircuit table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetSubcircuitUserFields()
```
### TelecomDomainNetwork

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Gets the telecom domain network that holds the circuits.</p>


```csharp
public TelecomDomainNetwork TelecomDomainNetwork { get; }
```
### Verify(IEnumerable&lt;string&gt;, CircuitVerifyOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.yml" sourcestartlinenumber="1">Verifies the specified circuits.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<CircuitVerifyResult> Verify(IEnumerable<string> circuitNames, CircuitVerifyOptions circuitVerifyOptions)
```


