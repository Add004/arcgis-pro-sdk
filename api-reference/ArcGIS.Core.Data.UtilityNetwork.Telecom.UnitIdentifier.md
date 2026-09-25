# UnitIdentifier

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifier.yml" sourcestartlinenumber="1">Specifies an identifier for a container or its contents as defined by the <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange" data-throw-if-not-resolved="false"></xref> in the telecom domain network.</p>


## Object Signature

```csharp
public sealed class UnitIdentifier
```


## Members

### UnitIdentifier(NetworkSource, Guid)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifier.yml" sourcestartlinenumber="1">Creates a new instance of <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifier" data-throw-if-not-resolved="false"></xref> with the specified network source and GlobalID.</p>


```csharp
public UnitIdentifier(NetworkSource networkSource, Guid globalID)
```
### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifier.yml" sourcestartlinenumber="1">Represents the GlobalID of the unit identifier.</p>


```csharp
public Guid GlobalID { get; }
```
### NetworkSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifier.yml" sourcestartlinenumber="1">Represents the network source that this unit identifier belongs to.</p>


```csharp
public NetworkSource NetworkSource { get; }
```


