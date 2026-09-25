# FeatureInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p>
    Represents the parent feature of a topological element.
    </p>
<p>
    A <i>parent feature</i> refers to a feature in the feature space from which one or more topological elements are
    created in the topology graph space.
    </p>


## Object Signature

```csharp
public sealed class FeatureInfo
```


## Members

### FeatureClassName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.FeatureInfo.yml" sourcestartlinenumber="1">The name of the feature class to which the parent feature belongs.</p>


```csharp
public string FeatureClassName { get; }
```
### GetFeature()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.FeatureInfo.yml" sourcestartlinenumber="1">Gets the complete parent <xref href="ArcGIS.Core.Data.Feature" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Feature GetFeature()
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.FeatureInfo.yml" sourcestartlinenumber="1">The object ID of the parent feature.</p>


```csharp
public long ObjectID { get; }
```


