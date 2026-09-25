# FunctionBarrier

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.yml" sourcestartlinenumber="1">A FunctionBarrier stops continued traversal when a comparison expression evaluates as true.</p>


## Object Signature

```csharp
public class FunctionBarrier
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.yml" sourcestartlinenumber="1">A FunctionBarrier performs a comparison expression between the current results of a <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.Function" data-throw-if-not-resolved="false"></xref> and a given value.</p>
<ul><li>Remember that a <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.Function" data-throw-if-not-resolved="false"></xref> references a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> and a function that is applied to it (<xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Min" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Max" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Count" data-throw-if-not-resolved="false"></xref>, etc.)</li><li>Once the comparison evaluates as true, network traversal stops.</li></ul>


## Members

### FunctionBarrier(Function, Operator, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public FunctionBarrier(Function function, Operator comparisonOperator, double value)
```
### Function

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Function" data-throw-if-not-resolved="false"></xref> to evaluate.</p>


```csharp
public Function Function { get; }
```
### Operator

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Operator" data-throw-if-not-resolved="false"></xref> used for the comparison.</p>


```csharp
public Operator Operator { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.yml" sourcestartlinenumber="1">Gets a text representation of this object.</p>


```csharp
public override string ToString()
```
### UseLocalValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.yml" sourcestartlinenumber="1">If True, local values are used in the functional comparison.</p>


```csharp
public bool UseLocalValues { get; set; }
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier.yml" sourcestartlinenumber="1">The value to compare against.</p>


```csharp
public double Value { get; }
```


