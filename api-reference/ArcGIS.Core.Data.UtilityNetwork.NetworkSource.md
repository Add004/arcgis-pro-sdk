# NetworkSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Represents a network source in a utility network.</p>


## Object Signature

```csharp
public sealed class NetworkSource : CoreObjectsBase, IDisposable
```

## Remarks

<ul>
  <li>One source of information in a utility network are the tables that make it up</li>
  <ul>
    <li>Structure feature classes: StructureLine, StructurePoint, and StructureBoundary</li>
    <li>Domain network feature classes: Device, Line, Junction, Assembly, and SubnetLine</li>
  </ul>
  <li>Another source of information is the set of associations that have been created</li>
  <li>The final source of information are the system junctions that are automatically generated where needed</li>
</ul>
<pre><code sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="11">Network sources should not be confused with subnetwork source, which is a source of resources (e.g., electricity or water).
Instances of Source objects can be obtained from &lt;xref href=&quot;ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; and &lt;xref href=&quot;ArcGIS.Core.Data.UtilityNetwork.DomainNetwork&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; objects.
</code></pre>


## Members

### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### GetAssetGroup(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetGroup" data-throw-if-not-resolved="false"></xref> object with the specified name.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AssetGroup GetAssetGroup(string assetGroupName)
```
### GetAssetGroups()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Gets a list of the <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetGroup" data-throw-if-not-resolved="false"></xref>s (subtypes) for this network source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<AssetGroup> GetAssetGroups()
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Gets a hash code for the current object.</p>


```csharp
public override int GetHashCode()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Gets the ID of the utility network source.</p>


```csharp
public int ID { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Gets the name of the utility network source.</p>


```csharp
public string Name { get; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.SourceType" data-throw-if-not-resolved="false"></xref> of the utility network source.</p>


```csharp
public SourceType Type { get; }
```
### UsageType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.NetworkSource.yml" sourcestartlinenumber="1">Gets the usage type of this network source.  This indicates how the source is used.</p>


```csharp
public SourceUsageType UsageType { get; }
```


