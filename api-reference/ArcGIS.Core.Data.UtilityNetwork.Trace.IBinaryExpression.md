# IBinaryExpression

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.IBinaryExpression.yml" sourcestartlinenumber="1">Represents a non-terminal <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.ConditionalExpression" data-throw-if-not-resolved="false"></xref> node that has a left expression and a right expression.</p>


## Object Signature

```csharp
public interface IBinaryExpression
```


## Members

### LeftExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.IBinaryExpression.yml" sourcestartlinenumber="1">The left side of this non-terminal <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.ConditionalExpression" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
ConditionalExpression LeftExpression { get; }
```
### RightExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.IBinaryExpression.yml" sourcestartlinenumber="1">The right side of this non-terminal <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.ConditionalExpression" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
ConditionalExpression RightExpression { get; }
```


