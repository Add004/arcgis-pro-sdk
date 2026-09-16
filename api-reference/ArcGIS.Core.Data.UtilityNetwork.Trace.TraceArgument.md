# TraceArgument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">The TraceArgument class consolidates all of the input parameters to a trace.</p>


## Object Signature

```csharp
public class TraceArgument
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Different <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer" data-throw-if-not-resolved="false"></xref> objects may subclass TraceArgument.</p>


## Members

### TraceArgument(Subnetwork)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>TraceArgument</code> class using a <code class="paramref">subnetwork</code>.</p>


```csharp
public TraceArgument(Subnetwork subnetwork)
```
### TraceArgument(Circuit)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>TraceArgument</code> class using a <code class="paramref">circuit</code>.</p>


```csharp
public TraceArgument(Circuit circuit)
```
### TraceArgument(NamedTraceConfiguration, Subnetwork)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>TraceArgument</code> class using a <code class="paramref">namedTraceConfiguration</code> and a <code class="paramref">subnetwork</code>.</p>


```csharp
public TraceArgument(NamedTraceConfiguration namedTraceConfiguration, Subnetwork subnetwork)
```
### TraceArgument(NamedTraceConfiguration, IEnumerable&lt;Element&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>TraceArgument</code> class using a <code class="paramref">namedTraceConfiguration</code> and <code class="paramref">startingLocations</code>.</p>


```csharp
public TraceArgument(NamedTraceConfiguration namedTraceConfiguration, IEnumerable<Element> startingLocations)
```
### TraceArgument(IEnumerable&lt;Element&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>TraceArgument</code> class using <code class="paramref">startingLocations</code>.</p>


```csharp
public TraceArgument(IEnumerable<Element> startingLocations)
```
### Barriers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">An optional set of <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> that acts as physical barriers to stop a trace.</p>


```csharp
public IReadOnlyList<Element> Barriers { get; set; }
```
### Circuit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">The circuit that will be used for the trace.</p>


```csharp
public Circuit Circuit { get; }
```
### Configuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Additional tracing configuration parameters</p>


```csharp
public TraceConfiguration Configuration { get; set; }
```
### FilterBarriers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">An optional set of <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> objects that act as filter barriers.  A regular barrier prevents traversal, which, when used with subnetwork-based traces, can prevent traversal to the
subnetwork controller. Like a <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Filter" data-throw-if-not-resolved="false"></xref>, filter barriers are evaluated in the second pass of a trace.  Therefore, it can restrict the result set without impacting the
ability to find subnetwork controllers from starting points.</p>


```csharp
public IReadOnlyList<Element> FilterBarriers { get; set; }
```
### ResultOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Additional field value information to be returned from a trace operation using the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.ResultType.Feature" data-throw-if-not-resolved="false"></xref> result type.</p>


```csharp
public ResultOptions ResultOptions { get; set; }
```
### ResultTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">Gets or sets the types of result for trace output.</p>


```csharp
public IReadOnlyList<ResultType> ResultTypes { get; set; }
```
### StartingLocations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">The starting locations from which to originate the trace.</p>


```csharp
public IReadOnlyList<Element> StartingLocations { get; }
```
### StoppingLocations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">The stopping locations from which to end the trace.</p>


```csharp
public IReadOnlyList<Element> StoppingLocations { get; set; }
```
### Subnetwork

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceArgument.yml" sourcestartlinenumber="1">The Subnetwork whose controllers is used to generate starting points for the trace.</p>


```csharp
public Subnetwork Subnetwork { get; }
```


