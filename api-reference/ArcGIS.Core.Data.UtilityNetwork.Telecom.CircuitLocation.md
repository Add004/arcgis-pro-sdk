# CircuitLocation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocation.yml" sourcestartlinenumber="1">Represents an <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> with unit information that is used with circuit management.</p>


## Object Signature

```csharp
public sealed class CircuitLocation
```


## Members

### CircuitLocation(Element)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocation.yml" sourcestartlinenumber="1">Creates a circuit location based on the associated circuit <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CircuitLocation(Element element)
```
### FirstUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocation.yml" sourcestartlinenumber="1">The first unit that the circuit location refers to.</p>


```csharp
public short? FirstUnit { get; set; }
```
### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocation.yml" sourcestartlinenumber="1">The GlobalID of the circuit location.</p>


```csharp
public Guid GlobalID { get; }
```
### LastUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocation.yml" sourcestartlinenumber="1">The last unit that the circuit location refers to.</p>


```csharp
public short? LastUnit { get; set; }
```
### NetworkSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocation.yml" sourcestartlinenumber="1">The network source that the circuit location belongs to.</p>


```csharp
public NetworkSource NetworkSource { get; }
```


