# TraverseAssociationsResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsResult.yml" sourcestartlinenumber="1">Represents a collection of <xref href="ArcGIS.Core.Data.UtilityNetwork.Association" data-throw-if-not-resolved="false"></xref>s and the mapping between involved <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref>s and their field name-values from an associations traversal operation.</p>


## Object Signature

```csharp
public sealed class TraverseAssociationsResult
```


## Members

### AdditionalFieldValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsResult.yml" sourcestartlinenumber="1">The mapping between a collection of <xref href="ArcGIS.Core.Data.UtilityNetwork.Element" data-throw-if-not-resolved="false"></xref> and their field name-value pairs specified by a <xref href="ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyDictionary<Element, IReadOnlyList<FieldValue>> AdditionalFieldValues { get; }
```
### Associations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsResult.yml" sourcestartlinenumber="1">The list of Association objects.</p>


```csharp
public IReadOnlyList<Association> Associations { get; }
```


