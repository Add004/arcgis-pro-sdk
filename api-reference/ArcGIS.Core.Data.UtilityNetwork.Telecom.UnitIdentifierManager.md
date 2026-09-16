# UnitIdentifierManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifierManager.yml" sourcestartlinenumber="1">Provides methods to manage unit identifiers <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifier" data-throw-if-not-resolved="false"></xref> within a telecom domain network.</p>


## Object Signature

```csharp
public sealed class UnitIdentifierManager : CoreObjectsBase, IDisposable
```


## Members

### Combine(IEnumerable&lt;TelecomElement&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifierManager.yml" sourcestartlinenumber="1">Combines the elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CombineResult Combine(IEnumerable<TelecomElement> telecomElements)
```
### Divide(TelecomElement, IEnumerable&lt;short&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifierManager.yml" sourcestartlinenumber="1">Divides the specified element.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DivideResult Divide(TelecomElement telecomElement, IEnumerable<short> numUnitsToDivide)
```
### Query(IEnumerable&lt;UnitIdentifier&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifierManager.yml" sourcestartlinenumber="1">Queries the content, <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange" data-throw-if-not-resolved="false"></xref> of an equipment container, such as ports (content) in a switch or slots (container) in a rack.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<UnitQueryResult> Query(IEnumerable<UnitIdentifier> containers)
```
### ReserveUnitIDs(UnitIdentifier, short, short)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifierManager.yml" sourcestartlinenumber="1">Reserves a range to create a gap in the unit range <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange" data-throw-if-not-resolved="false"></xref> space of an equipment container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ReserveUnitIDs(UnitIdentifier container, short firstUnit, short lastUnit)
```
### Reset(IEnumerable&lt;UnitIdentifier&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifierManager.yml" sourcestartlinenumber="1">Removes gaps and resets the unit space to be contiguous within an equipment hierarchy.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Reset(IEnumerable<UnitIdentifier> containers)
```
### Resize(UnitIdentifier, short)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifierManager.yml" sourcestartlinenumber="1">Updates the number of units in an equipment container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Resize(UnitIdentifier content, short lastUnit)
```


