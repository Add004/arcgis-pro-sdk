# RangeRelation

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.RangeRelation.yml" sourcestartlinenumber="1">Range relation types.</p>


## Object Signature

```csharp
public enum RangeRelation
```


## Members

### AfterStartOverlapsEnd

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.RangeRelation.yml" sourcestartlinenumber="1">Include values equal to the end and values that are between the start and end.</p>


```csharp
AfterStartOverlapsEnd = 2
```
### Overlaps

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.RangeRelation.yml" sourcestartlinenumber="1">Include values equal to the start or end and values that are between the start and end.</p>


```csharp
Overlaps = 0
```
### OverlapsStartWithinEnd

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.RangeRelation.yml" sourcestartlinenumber="1">Include values equal to the start and values that are between the start and end.</p>


```csharp
OverlapsStartWithinEnd = 1
```
### Within

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.RangeRelation.yml" sourcestartlinenumber="1">Include values that are between the start and end but not equal to either.</p>


```csharp
Within = 3
```


