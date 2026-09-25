# SubnetworkExportOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Represents a mechanism to export a <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class SubnetworkExportOptions : ExportOptions
```


## Members

### SubnetworkExportOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>SubnetworkExportOptions</code> class to export a <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SubnetworkExportOptions()
```
### IncludeFlowDirections

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Specifies whether to include flow direction results.</p>


```csharp
public bool IncludeFlowDirections { get; set; }
```
### IncludeGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Specifies whether geometry will be included in the results.</p>


```csharp
public bool IncludeGeometry { get; set; }
```
### IncludePropagatedValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Specifies whether to include propagated value results.</p>


```csharp
public bool IncludePropagatedValues { get; set; }
```
### RelatedRecordFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Specifies additional related record field values to be returned during export.</p>


```csharp
public Dictionary<RelationshipClass, List<string>> RelatedRecordFields { get; set; }
```
### ResultFieldsByNetworkSourceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">The names of the fields from a network source that will be returned as results.</p>


```csharp
public Dictionary<int, List<string>> ResultFieldsByNetworkSourceID { get; set; }
```
### ResultNetworkAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">The network attributes that will be included in the results.</p>


```csharp
public List<NetworkAttribute> ResultNetworkAttributes { get; set; }
```
### SetAcknowledged

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Specifies whether the export is acknowledged. If <code>true</code> the default version is required.</p>


```csharp
public bool SetAcknowledged { get; set; }
```
### SubnetworkExportResultTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkExportOptions.yml" sourcestartlinenumber="1">Specifies the types of results that will be returned.</p>


```csharp
public List<SubnetworkExportResultType> SubnetworkExportResultTypes { get; set; }
```


