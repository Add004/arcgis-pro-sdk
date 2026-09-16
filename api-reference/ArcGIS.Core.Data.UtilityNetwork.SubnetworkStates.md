# SubnetworkStates

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">Allowable states for subnetworks.</p>


## Object Signature

```csharp
[Flags]
public enum SubnetworkStates
```


## Members

### All

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">A combination of the values in this list; provides an easy way to fetch all of the subnetworks in a <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
All = InvalidSubnetworkObject | Dirty | Clean | CleanAndAcknowledged | DirtyAndDeleted | CleanAndDeleted | InvalidWithErrors
```
### Clean

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1"><xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork.Update" data-throw-if-not-resolved="false"></xref> has been run subsequent to any edits made to this subnetwork.</p>


```csharp
Clean = 4
```
### CleanAndAcknowledged

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">Export with the SetAcknowledgedFlag has been run after <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork.Update" data-throw-if-not-resolved="false"></xref> and before additional edits.</p>


```csharp
CleanAndAcknowledged = 8
```
### CleanAndDeleted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">All subnetworks controllers have been dropped from the subnetwork, but Export has not been run with the SetAcknowledged flag.  Once a subnetwork is in this state, running Export with
the SetAcknowledged flag will delete the subnetwork.</p>


```csharp
CleanAndDeleted = 32
```
### Dirty

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">Changes have been made to features within the subnetwork.</p>


```csharp
Dirty = 2
```
### DirtyAndDeleted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">All subnetwork controllers have been droped from the subnetwork, but <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork.Update" data-throw-if-not-resolved="false"></xref> has not yet been run.</p>


```csharp
DirtyAndDeleted = 16
```
### InvalidSubnetworkObject

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">The subnetwork has been completely deleted (no database rows exist), but the <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref> object remains.  Once a subnetwork is in this state, most properties and methods on the <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref> object will throw an exception.</p>


```csharp
InvalidSubnetworkObject = 1
```
### InvalidWithErrors

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates.yml" sourcestartlinenumber="1">The subnetwork has been updated, and an error condition was discovered. Once the subnetwork is in this state, it cannot be updated until edits have been made to correct the error condition and validation has been run successfully.</p>


```csharp
InvalidWithErrors = 64
```


