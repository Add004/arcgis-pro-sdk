# Or

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Or.yml" sourcestartlinenumber="1">The Or conditional expression is used to perform boolean logic with other conditional expressions.</p>


## Object Signature

```csharp
public sealed class Or : ConditionalExpression, IBinaryExpression
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Or.yml" sourcestartlinenumber="1">The Or conditional expression returns True if either of the constituent expressions returns True.<br>
If both of the constituent expressions return False, the Or conditional expression returns false.</p>


## Members

### Or(ConditionalExpression, ConditionalExpression)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Or.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Or" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public Or(ConditionalExpression leftExpression, ConditionalExpression rightExpression)
```
### LeftExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Or.yml" sourcestartlinenumber="1">The left side of this <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Or" data-throw-if-not-resolved="false"></xref> expression.</p>


```csharp
public ConditionalExpression LeftExpression { get; }
```
### RightExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Or.yml" sourcestartlinenumber="1">The right side of this <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Or" data-throw-if-not-resolved="false"></xref> expression.</p>


```csharp
public ConditionalExpression RightExpression { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Or.yml" sourcestartlinenumber="1">Gets a text representation of this object.</p>


```csharp
public override string ToString()
```


