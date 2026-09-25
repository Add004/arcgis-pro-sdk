# Function

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">Functions allow the computation of values during a network trace.</p>


## Object Signature

```csharp
public abstract class Function
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">Functions are evaluated at each <i>applicable</i> network element.  The meaning of <i>applicable</i> varies depending on the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer" data-throw-if-not-resolved="false"></xref>.</p>
<ul><li>For an <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer" data-throw-if-not-resolved="false"></xref>, the functions are evaluated for each upstream element.</li><li>For a <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.SubnetworkTracer" data-throw-if-not-resolved="false"></xref>, the functions are evaluated for each element in the subnetwork.</li><li>For a <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.SubnetworkControllerTracer" data-throw-if-not-resolved="false"></xref>, the functions are evaluated for each subnetwork source element.</li><li>etc.</li></ul>
<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="5">At the conclusion of the trace, function results can obtained using the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionOutputResult" data-throw-if-not-resolved="false"></xref> class.</p>


## Members

### Function(NetworkAttribute)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Function" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
protected Function(NetworkAttribute networkAttribute)
```
### Function(NetworkAttribute, Condition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Function" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
protected Function(NetworkAttribute networkAttribute, Condition condition)
```
### Condition

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">If set, this property restricts the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Function" data-throw-if-not-resolved="false"></xref> calculation to features that satisfy the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Function.Condition" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Condition Condition { get; }
```
### FunctionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">Gets or sets the alias name of the function.</p>


```csharp
public string FunctionName { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">The name of the Function.</p>


```csharp
public abstract string Name { get; }
```
### NetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Function.NetworkAttribute" data-throw-if-not-resolved="false"></xref> used as an input to the Function.</p>


```csharp
public NetworkAttribute NetworkAttribute { get; }
```
### PersistedField

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">The field on the SubnetLine classes where the function value is stored during the update subnetwork process.</p>


```csharp
public Field PersistedField { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Function.yml" sourcestartlinenumber="1">Gets a text representation of this object.</p>


```csharp
public override string ToString()
```


