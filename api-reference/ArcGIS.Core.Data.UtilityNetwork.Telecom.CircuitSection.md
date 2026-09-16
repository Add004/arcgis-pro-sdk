# CircuitSection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Represents a circuit section that either has or has not been created yet.</p>


## Object Signature

```csharp
public sealed class CircuitSection : CoreObjectsBase, IDisposable
```


## Members

### CircuitSection(CircuitManager)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Constructs a circuit section object.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitSection(CircuitManager circuitManager)
```
### GetGlobalID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets the GlobalID of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Guid GetGlobalID()
```
### GetSectionID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets the section ID of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetSectionID()
```
### GetSectionRole()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets the circuit section role.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitSectionRole GetSectionRole()
```
### GetSectionType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets the circuit section type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitSectionType GetSectionType()
```
### GetStartLocation()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets the start location of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitLocation GetStartLocation()
```
### GetStopLocation()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets the stop location of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CircuitLocation GetStopLocation()
```
### GetSubcircuit()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets the subcircuit of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Subcircuit GetSubcircuit()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets or sets the value of a user field at the given index.
This property must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[int index] { get; set; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Gets or sets the value of a user field with the given name or alias.
This property must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[string fieldName] { get; set; }
```
### SetGlobalID(Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Sets the GlobalID of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGlobalID(Guid globalID)
```
### SetSectionType(CircuitSectionType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Sets the section type of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSectionType(CircuitSectionType circuitSectionType)
```
### SetStartLocation(CircuitLocation)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Sets the start location of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStartLocation(CircuitLocation startLocation)
```
### SetStopLocation(CircuitLocation)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Sets the stop location of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStopLocation(CircuitLocation stopLocation)
```
### SetSubcircuit(Subcircuit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitSection.yml" sourcestartlinenumber="1">Sets the subcircuit of the circuit section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSubcircuit(Subcircuit subcircuit)
```


