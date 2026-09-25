# Subcircuit

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Represents a circuit that either has or has not been created yet.</p>


## Object Signature

```csharp
public sealed class Subcircuit : CoreObjectsBase, IDisposable
```


## Members

### Subcircuit(CircuitManager)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Constructs a subcircuit object.</p>


```csharp
public Subcircuit(CircuitManager circuitManager)
```
### GetConsumerID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Gets the GlobalID of the subcircuit's consumer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Guid GetConsumerID()
```
### GetGlobalID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Gets the GlobalID of the subcircuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Guid GetGlobalID()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Gets the name of the subcircuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### GetProviderID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Gets the GlobalID of the subcircuit's provider.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Guid GetProviderID()
```
### GetState()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Gets the state.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SubcircuitState GetState()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Gets and sets the value of a user field with the given index.
This property must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[int index] { get; set; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Gets and sets the value of a user field with the given name or alias.
This property must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[string fieldName] { get; set; }
```
### SetGlobalID(Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Sets the GlobalID of the subcircuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGlobalID(Guid globalID)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Sets the name of the subcircuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetName(string name)
```
### SetProviderID(Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Sets the GlobalID of the subcircuit's provider.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetProviderID(Guid providerID)
```
### SetState(SubcircuitState)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.Subcircuit.yml" sourcestartlinenumber="1">Sets the state of the subcircuit.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetState(SubcircuitState state)
```


