# DiagramElementAttributeValues

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues.yml" sourcestartlinenumber="1">Represents the attribute value(s) of a diagram element and its aggregated elements .</p>


## Object Signature

```csharp
public sealed class DiagramElementAttributeValues
```


## Members

### DiagramElementAttributeValues(int, object[], List&lt;object[]&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public DiagramElementAttributeValues(int ID, object[] values, List<object[]> aggregatedElementsValues)
```
### AggregatedElementsValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues.yml" sourcestartlinenumber="1">Gets the list of attribute values for aggregated elements of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<object[]> AggregatedElementsValues { get; }
```
### ElementID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues.yml" sourcestartlinenumber="1">Gets the ID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElement" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int ElementID { get; }
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues.yml" sourcestartlinenumber="1">Gets the array of element attribute values of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public object[] Values { get; }
```


