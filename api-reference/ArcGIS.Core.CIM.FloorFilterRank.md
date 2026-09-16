# FloorFilterRank

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.FloorFilterRank.yml" sourcestartlinenumber="1">Represents the rank or &quot;level&quot; at which the layer participates in filtering for Indoors or floor-aware layers.</p>


## Object Signature

```csharp
public enum FloorFilterRank
```


## Members

### Facility

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FloorFilterRank.yml" sourcestartlinenumber="1">Layer is an Indoors Facility layer and will be filtered according to the selected facility or facilities within the selected site.</p>


```csharp
Facility = 2
```
### Level

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FloorFilterRank.yml" sourcestartlinenumber="1">Layer is a &quot;floor-aware&quot; layer and will be filtered according to the selected level or levels within the selected site.</p>


```csharp
Level = 3
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FloorFilterRank.yml" sourcestartlinenumber="1">Does not participate in floor filtering.</p>


```csharp
None = 0
```
### Site

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FloorFilterRank.yml" sourcestartlinenumber="1">Layer is an Indoors Site layer and will be filtered according to the selected site.</p>


```csharp
Site = 1
```


