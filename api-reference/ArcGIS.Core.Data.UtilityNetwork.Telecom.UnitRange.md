# UnitRange

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange.yml" sourcestartlinenumber="1">Represents a span of units in container equipment. These can represent ports in a switch or slots in a rack.</p>


## Object Signature

```csharp
public sealed class UnitRange
```


## Members

### Content

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange.yml" sourcestartlinenumber="1">Represents the content of the equipment.</p>


```csharp
public UnitIdentifier Content { get; }
```
### FirstUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange.yml" sourcestartlinenumber="1">Represents the first unit in the range.</p>


```csharp
public short? FirstUnit { get; }
```
### IsGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange.yml" sourcestartlinenumber="1">Represents whether the unit range is a gap (true) or not (false).</p>


```csharp
public bool IsGap { get; }
```
### LastUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange.yml" sourcestartlinenumber="1">Represents the last unit in the range.</p>


```csharp
public short? LastUnit { get; }
```


