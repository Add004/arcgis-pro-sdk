# AssetType

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets information about the definition of an Asset Type.</p>


## Object Signature

```csharp
public sealed class AssetType : CoreObjectsBase, IDisposable
```


## Members

### AssetGroup

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the parent <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetGroup" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AssetGroup AssetGroup { get; }
```
### AssociationDeletionSemantics

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the association deletion type of this asset type.</p>


```csharp
public AssociationDeleteType AssociationDeletionSemantics { get; }
```
### AssociationRoleType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType.AssociationRoleType" data-throw-if-not-resolved="false"></xref> of this asset type. This indicates whether the asset type can be a Container, Structure, or neither.</p>


```csharp
public AssociationRoleType AssociationRoleType { get; }
```
### CategoryList

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets a list of categories supported by this asset type.</p>


```csharp
public IReadOnlyList<string> CategoryList { get; }
```
### Code

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the ID of this asset type.</p>


```csharp
public int Code { get; }
```
### ContainerViewScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the default scale of any containers created from this asset type.</p>


```csharp
public double ContainerViewScale { get; }
```
### GetContainerSplitPolicy()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the type of <xref href="ArcGIS.Core.Data.UtilityNetwork.ContainerSplitPolicy" data-throw-if-not-resolved="false"></xref> this instance of AssetType supports.</p>


```csharp
public ContainerSplitPolicy GetContainerSplitPolicy()
```
### GetLinearConnectivityPolicy()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.ConnectivityPolicy" data-throw-if-not-resolved="false"></xref> supported by this asset type.</p>


```csharp
public ConnectivityPolicy GetLinearConnectivityPolicy()
```
### GetTerminalConfiguration()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration" data-throw-if-not-resolved="false"></xref> supported by this asset type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TerminalConfiguration GetTerminalConfiguration()
```
### IsContainerSplitPolicySupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets a value indicating whether this instance of AssetType supports a policy where a container can split its contents
(e.g., structure network line features).</p>


```csharp
public bool IsContainerSplitPolicySupported()
```
### IsLinearConnectivityPolicySupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets whether or not the <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType.GetLinearConnectivityPolicy" data-throw-if-not-resolved="false"></xref> method will return a meaningful result.</p>


```csharp
public bool IsLinearConnectivityPolicySupported()
```
### IsTerminalConfigurationSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets whether or not the <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType.GetTerminalConfiguration" data-throw-if-not-resolved="false"></xref> method will return a meaningful result.</p>


```csharp
public bool IsTerminalConfigurationSupported()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetType.yml" sourcestartlinenumber="1">Gets the name of the asset type.</p>


```csharp
public string Name { get; }
```


