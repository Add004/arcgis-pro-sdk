# FullTextOrExpression

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.FullTextOrExpression.yml" sourcestartlinenumber="1"><code>FullTextOrExpression</code> is used to combine full-text search conditions using OR logic.</p>


## Object Signature

```csharp
public sealed class FullTextOrExpression : FullTextExpression
```


## Members

### FullTextOrExpression(FullTextExpression, FullTextExpression)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.FullTextOrExpression.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.FullTextOrExpression" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public FullTextOrExpression(FullTextExpression leftExpression, FullTextExpression rightExpression)
```
### LeftExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FullTextOrExpression.yml" sourcestartlinenumber="1">Gets the left expression of <xref href="ArcGIS.Core.Data.FullTextOrExpression" data-throw-if-not-resolved="false"></xref></p>


```csharp
public FullTextExpression LeftExpression { get; }
```
### RightExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FullTextOrExpression.yml" sourcestartlinenumber="1">Gets the right expression of <xref href="ArcGIS.Core.Data.FullTextOrExpression" data-throw-if-not-resolved="false"></xref></p>


```csharp
public FullTextExpression RightExpression { get; }
```


