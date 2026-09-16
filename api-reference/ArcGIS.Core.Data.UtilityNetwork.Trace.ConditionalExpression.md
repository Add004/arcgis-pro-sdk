# ConditionalExpression

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.ConditionalExpression.yml" sourcestartlinenumber="1">The ConditionalExpression class is an abstract base class that represents a Boolean condition composed of one or more comparison clauses.  It is used in conjunction with tracing in different contexts- including control of traversability and control of applicability of functional expressions.</p>


## Object Signature

```csharp
public abstract class ConditionalExpression : Condition
```

## Remarks

<ul>
  <li>The <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison" data-throw-if-not-resolved="false"></xref> subclass is based on comparisons of network attributes.</li>
  <li>The <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison" data-throw-if-not-resolved="false"></xref> subclass is based on checking for an assigned category.</li>
  <li>ConditionalExpressions can be combined with the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.And" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Or" data-throw-if-not-resolved="false"></xref> subclasses to form more complex conditions.</li>
</ul>


## Members

### ConditionalExpression()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.ConditionalExpression.yml" sourcestartlinenumber="1">The ConditionalExpression class is an abstract base class that represents a Boolean condition composed of one or more comparison clauses.  It is used in conjunction with tracing in different contexts- including control of traversability and control of applicability of functional expressions.</p>


```csharp
protected ConditionalExpression()
```


