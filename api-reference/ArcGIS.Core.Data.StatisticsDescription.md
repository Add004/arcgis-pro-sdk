# StatisticsDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.StatisticsDescription.yml" sourcestartlinenumber="1">Specifies what statistics function(s) should be performed on a specific field.</p>


## Object Signature

```csharp
public sealed class StatisticsDescription
```


## Members

### StatisticsDescription(Field, IEnumerable&lt;StatisticsFunction&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.StatisticsDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>StatisticsDescription</code> class.</p>


```csharp
public StatisticsDescription(Field field, IEnumerable<StatisticsFunction> statisticsFunctions)
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> upon which statistics functions are performed.</p>


```csharp
public Field Field { get; }
```
### StatisticsFunctions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsDescription.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.StatisticsFunction" data-throw-if-not-resolved="false"></xref>s to be performed.</p>


```csharp
public IReadOnlyList<StatisticsFunction> StatisticsFunctions { get; }
```


