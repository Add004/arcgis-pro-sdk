# CategoryComparison

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison.yml" sourcestartlinenumber="1">The CategoryComparison conditional expression performs a comparison that checks to see if a Category is assigned to the <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> of the current row</p>


## Object Signature

```csharp
public sealed class CategoryComparison : ConditionalExpression
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison.yml" sourcestartlinenumber="1">For example, you could create a CategoryComparison object that checks to see if a row is assigned the Valve category.</p>


## Members

### CategoryComparison(CategoryOperator, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public CategoryComparison(CategoryOperator comparisonOperator, string category)
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison.yml" sourcestartlinenumber="1">The Category to use in the comparison</p>


```csharp
public string Category { get; }
```
### Operator

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison.yml" sourcestartlinenumber="1">The operator to use in the comparison (equals, not equals).</p>


```csharp
public CategoryOperator Operator { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison.yml" sourcestartlinenumber="1">Gets a text representation of this object.</p>


```csharp
public override string ToString()
```


