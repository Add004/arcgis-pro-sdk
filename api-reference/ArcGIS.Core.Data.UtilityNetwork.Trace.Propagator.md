# Propagator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">Propagator objects allow a subset of NetworkAttribute values to propagate through a network while executing a trace.  These values can be tested to allow or disallow further traversal.</p>


## Object Signature

```csharp
public class Propagator
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">The canonical example is phase propagation- open devices along the network will restrict some phases from continuing along the trace. Propagators are only applicable to subnetwork-based traces
(<xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.SubnetworkTracer" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer" data-throw-if-not-resolved="false"></xref>, etc.).</p>


## Members

### Propagator(NetworkAttribute, PropagatorFunction, Operator, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>Propagator</code> class.</p>


```csharp
public Propagator(NetworkAttribute networkAttribute, PropagatorFunction propagatorFunction, Operator comparisonOperator, double value)
```
### Propagator(NetworkAttribute, PropagatorFunction, Operator, double, NetworkAttribute)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>Propagator</code> class.</p>


```csharp
public Propagator(NetworkAttribute networkAttribute, PropagatorFunction propagatorFunction, Operator comparisonOperator, double value, NetworkAttribute substitutionAttribute)
```
### Propagator(NetworkAttribute, PropagatorFunction, Operator, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>Propagator</code> class.</p>


```csharp
public Propagator(NetworkAttribute networkAttribute, PropagatorFunction propagatorFunction, Operator comparisonOperator, string value)
```
### NetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> to propagate downstream from the source.</p>


```csharp
public NetworkAttribute NetworkAttribute { get; }
```
### Operator

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">The filter operator that is applied when executing the trace.  This operator is used to compare the propagated value to the specified <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.Value" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Operator Operator { get; }
```
### PersistedField

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">The field on the domain network feature classes where the propagated value is stored.</p>


```csharp
public Field PersistedField { get; }
```
### PropagatorFunction

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">The function that is applied to the <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> to propagate the attribute downstream.</p>


```csharp
public PropagatorFunction PropagatorFunction { get; }
```
### SubstitutionAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">Gets or sets a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> that maps each bit in another bitset network attribute value to a new value.</p>


```csharp
public NetworkAttribute SubstitutionAttribute { get; set; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">Gets a text representation of this object.</p>


```csharp
public override string ToString()
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">The value that is compared against the propagated value when executing the trace.</p>


```csharp
public double Value { get; }
```
### WavelengthValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator.yml" sourcestartlinenumber="1">The wavelength value that is compared against the propagated value when executing the trace.</p>


```csharp
public string WavelengthValue { get; }
```


