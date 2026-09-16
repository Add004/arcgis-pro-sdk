# SubnetworkController

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.yml" sourcestartlinenumber="1">Represents subnetwork controller.</p>


## Object Signature

```csharp
public sealed class SubnetworkController
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.yml" sourcestartlinenumber="1">A subnetwork controller is a device feature that serves as a source or sink for a <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref>.  Each subnetwork contains one or more subnetwork controllers.
Subnetwork controllers are added or removed by using <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.EnableController(ArcGIS.Core.Data.UtilityNetwork.Tier%2cArcGIS.Core.Data.UtilityNetwork.Element%2cSystem.String%2cSystem.String%2cSystem.String%2cSystem.String)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.DisableController(ArcGIS.Core.Data.UtilityNetwork.Element)" data-throw-if-not-resolved="false"></xref>, respectively.</p>


## Members

### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.yml" sourcestartlinenumber="1">A description string for the subnetwork controller.</p>


```csharp
public string Description { get; }
```
### Element

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.yml" sourcestartlinenumber="1">Returns the <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.Element" data-throw-if-not-resolved="false"></xref> that serves as this subnetwork controller.</p>


```csharp
public Element Element { get; }
```
### IsDeleted

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.yml" sourcestartlinenumber="1">Returns whether the subnetwork controller has been deleted.</p>


```csharp
public bool IsDeleted { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.yml" sourcestartlinenumber="1">Returns the name of the subnetwork controller.</p>


```csharp
public string Name { get; }
```
### Notes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkController.yml" sourcestartlinenumber="1">A notes string for the subnetwork controller.</p>


```csharp
public string Notes { get; }
```


