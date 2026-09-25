# And

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.And.yml" sourcestartlinenumber="1">The And conditional expression is used to perform boolean logic with other conditional expressions.</p>


## Object Signature

```csharp
public sealed class And : ConditionalExpression, IBinaryExpression
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.And.yml" sourcestartlinenumber="1">The And conditional expression returns True if both of the constituent expressions return True.<br>
If either or both of the constituent expressions returns False, the And conditional expression returns false.</p>


## Members

### And(ConditionalExpression, ConditionalExpression)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.And.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.And" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public And(ConditionalExpression leftExpression, ConditionalExpression rightExpression)
```
### LeftExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.And.yml" sourcestartlinenumber="1">The left side of this <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.And" data-throw-if-not-resolved="false"></xref> expression.</p>


```csharp
public ConditionalExpression LeftExpression { get; }
```
### RightExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.And.yml" sourcestartlinenumber="1">The right side of this <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.And" data-throw-if-not-resolved="false"></xref> expression.</p>


```csharp
public ConditionalExpression RightExpression { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.And.yml" sourcestartlinenumber="1">Gets a text representation of this object.</p>


```csharp
public override string ToString()
```


