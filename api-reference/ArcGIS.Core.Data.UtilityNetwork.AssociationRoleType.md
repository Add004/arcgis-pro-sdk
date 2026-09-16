# AssociationRoleType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationRoleType.yml" sourcestartlinenumber="1">Specifies whether a particular <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> can be a container, structure, or neither.</p>


## Object Signature

```csharp
public enum AssociationRoleType
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationRoleType.yml" sourcestartlinenumber="1">Returned from <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType.AssociationRoleType" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Container

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationRoleType.yml" sourcestartlinenumber="1">The asset type can participate as a container.</p>


```csharp
Container = 1
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationRoleType.yml" sourcestartlinenumber="1">The asset type cannot participate as a container or structure.</p>


```csharp
None = 0
```
### Structure

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationRoleType.yml" sourcestartlinenumber="1">The asset type can participate as a structure.</p>


```csharp
Structure = 2
```


