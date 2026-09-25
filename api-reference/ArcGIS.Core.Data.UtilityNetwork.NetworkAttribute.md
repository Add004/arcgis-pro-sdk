# NetworkAttribute

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">The NetworkAttribute class is used to represent a network attribute inside a utility network.  Network attributes correspond to weights in the geometric network.
NetworkAttribute objects can be obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetNetworkAttributes" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetNetworkAttribute(System.String)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class NetworkAttribute : CoreObjectsBase, IDisposable
```


## Members

### Assignments

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets a set of <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttributeAssignment" data-throw-if-not-resolved="false"></xref> objects that describe the assignments of this network attribute.</p>


```csharp
public IReadOnlyList<NetworkAttributeAssignment> Assignments { get; }
```
### CreationTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets the creation time of the network attribute.</p>


```csharp
public DateTime CreationTime { get; }
```
### Domain

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Domain" data-throw-if-not-resolved="false"></xref> associated with this network attribute.  If no domain is assigned, <b>null</b> is returned.</p>


```csharp
public Domain Domain { get; }
```
### IsApportionable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets a value indicating whether the network attribute should be apportioned across the length of linear features.</p>


```csharp
public bool IsApportionable { get; }
```
### IsInline

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets a value indicating whether the network attribute is stored inline with other topology information.</p>


```csharp
public bool IsInline { get; }
```
### IsNullable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets a value indicating whether the network attribute can contain null values.</p>


```csharp
public bool IsNullable { get; }
```
### IsSubstitution

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets a value indicating whether the network attribute is used to substitute another network attribute at a tap.</p>


```csharp
public bool IsSubstitution { get; }
```
### IsSystemAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets a value indicating whether the network attribute is system-maintained.</p>


```csharp
public bool IsSystemAttribute { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets the name of the network attribute.</p>


```csharp
public string Name { get; }
```
### NetworkAttributeToSubstitute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">If <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.IsSubstitution" data-throw-if-not-resolved="false"></xref> is true, this is the network attribute that is substituted by this one.</p>


```csharp
public NetworkAttribute NetworkAttributeToSubstitute { get; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute.yml" sourcestartlinenumber="1">Gets the data type of the network attribute.</p>


```csharp
public NetworkAttributeDataType Type { get; }
```


