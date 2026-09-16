# AssociationDeleteType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationDeleteType.yml" sourcestartlinenumber="1">Determines the behavior that occurs when attempting to delete a feature which has containment or structural attachment associations to other features.</p>


## Object Signature

```csharp
public enum AssociationDeleteType
```


## Members

### Cascade

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationDeleteType.yml" sourcestartlinenumber="1">The associated features are deleted.</p>


```csharp
Cascade = 0
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationDeleteType.yml" sourcestartlinenumber="1">Any associated features will not be deleted, but the associations will no longer exist. Default for structures.</p>


```csharp
None = 1
```
### Restricted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationDeleteType.yml" sourcestartlinenumber="1">If the feature has any associations, deleting the feature will fail. Default for containers.</p>


```csharp
Restricted = 2
```


