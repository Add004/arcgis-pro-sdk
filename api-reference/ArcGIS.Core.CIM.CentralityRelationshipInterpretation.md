# CentralityRelationshipInterpretation

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CentralityRelationshipInterpretation.yml" sourcestartlinenumber="1">Specifies the way relationships are interpreted for centrality computations.</p>


## Object Signature

```csharp
public enum CentralityRelationshipInterpretation
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CentralityRelationshipInterpretation.yml" sourcestartlinenumber="1"><xref href="ArcGIS.Core.CIM.CentralityMeasure.Coreness" data-throw-if-not-resolved="false"></xref> is only compatible with <xref href="ArcGIS.Core.CIM.CentralityRelationshipInterpretation.Undirected" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Directed

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.CentralityRelationshipInterpretation.yml" sourcestartlinenumber="1">Relationships are considered to be directed.</p>


```csharp
Directed = 1
```
### Reversed

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.CentralityRelationshipInterpretation.yml" sourcestartlinenumber="1">Relationships are considered to be directed and their direction is reversed.</p>


```csharp
Reversed = 2
```
### Undirected

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.CentralityRelationshipInterpretation.yml" sourcestartlinenumber="1">Relationships are considered to be undirected.</p>


```csharp
Undirected = 0
```


