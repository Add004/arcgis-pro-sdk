# esriDirectionsOutputType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.esriDirectionsOutputType.yml" sourcestartlinenumber="1">Network directions output type.</p>


## Object Signature

```csharp
public enum esriDirectionsOutputType
```


## Members

### esriDOTComplete

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriDirectionsOutputType.yml" sourcestartlinenumber="1">Directions output that includes all directions properties.</p>


```csharp
esriDOTComplete = 1
```
### esriDOTCompleteNoEvents

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriDirectionsOutputType.yml" sourcestartlinenumber="1">Directions output that includes all directions properties except events.</p>


```csharp
esriDOTCompleteNoEvents = 2
```
### esriDOTInstructionsOnly

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriDirectionsOutputType.yml" sourcestartlinenumber="1">Directions output that includes text instructions, time, length and ETA. Does not include geometry.</p>


```csharp
esriDOTInstructionsOnly = 3
```
### esriDOTStandard

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriDirectionsOutputType.yml" sourcestartlinenumber="1">Standard directions output – direction text instructions, geometry, time, length, ETA. Does not include events, new types of strings (street names, signposts info), Maneuver type, Bearings and Turn angle.</p>


```csharp
esriDOTStandard = 0
```
### esriDOTSummaryOnly

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriDirectionsOutputType.yml" sourcestartlinenumber="1">Directions output that contains only summary (time and length). Detailed text instructions and geometry are not provided.</p>


```csharp
esriDOTSummaryOnly = 4
```


