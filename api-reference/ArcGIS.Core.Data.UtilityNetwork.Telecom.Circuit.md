# Circuit

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Represents a circuit that may or may not have been created yet.</p>


## Object Signature

```csharp
public sealed class Circuit : CoreObjectsBase, IDisposable
```


## Members

### Circuit(CircuitManager)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public Circuit(CircuitManager circuitManager)
```
### GetCircuitSections()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the circuit sections dictionary representing the logical connectivity between circuit sections as a directed adjacency list.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<CircuitSection, List<CircuitSection>> GetCircuitSections()
```
### GetCircuitType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the circuit type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitType GetCircuitType()
```
### GetGlobalID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the GlobalID of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Guid GetGlobalID()
```
### GetLastAcknowledgedExport()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the date and time of the last acknowledged circuit export.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DateTime GetLastAcknowledgedExport()
```
### GetLastVerified()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the date and time when the circuit was last verified.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DateTime GetLastVerified()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the name of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### GetStartLocation()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the start location of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitLocation GetStartLocation()
```
### GetStatus()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the status of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitStatus GetStatus()
```
### GetStopLocation()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the stop location of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitLocation GetStopLocation()
```
### GetSubcircuits()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets the subcircuits.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Subcircuit> GetSubcircuits()
```
### IsSectioned()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets whether the circuit is sectioned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsSectioned()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets or sets the value of a user field at the given index.
This property must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[int index] { get; set; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Gets or sets the value of a user field with the given name or alias.
This property must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[string fieldName] { get; set; }
```
### SetCircuitSections(IReadOnlyDictionary&lt;CircuitSection, List&lt;CircuitSection&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Sets the circuit sections.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCircuitSections(IReadOnlyDictionary<CircuitSection, List<CircuitSection>> circuitSections)
```
### SetCircuitType(CircuitType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Sets the circuit type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCircuitType(CircuitType circuitType)
```
### SetGlobalID(Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Sets the GlobalID of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGlobalID(Guid globalID)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Sets the name of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetName(string name)
```
### SetSectioned(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Sets whether the circuit is sectioned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSectioned(bool isSectioned)
```
### SetStartLocation(CircuitLocation)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Sets the start location of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStartLocation(CircuitLocation startLocation)
```
### SetStopLocation(CircuitLocation)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Sets the stop location of the circuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStopLocation(CircuitLocation stopLocation)
```
### SetSubcircuits(IEnumerable&lt;Subcircuit&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Circuit.yml" sourcestartlinenumber="1">Sets the subcircuits.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSubcircuits(IEnumerable<Subcircuit> subcircuits)
```


