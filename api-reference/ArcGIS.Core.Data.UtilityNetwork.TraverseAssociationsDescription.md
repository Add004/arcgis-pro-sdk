# TraverseAssociationsDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsDescription.yml" sourcestartlinenumber="1">Represents a mechanism to return <xref href="ArcGIS.Core.Data.UtilityNetwork.Association" data-throw-if-not-resolved="false"></xref> objects in a specified <xref href="ArcGIS.Core.Data.UtilityNetwork.TraversalDirection" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TraverseAssociationsDescription
```


## Members

### TraverseAssociationsDescription(TraversalDirection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsDescription.yml" sourcestartlinenumber="1">Initializes a new instance of <code>TraverseAssociationsDescription</code> with a full traversal in a specified <xref href="ArcGIS.Core.Data.UtilityNetwork.TraversalDirection" data-throw-if-not-resolved="false"></xref> with the maximum depth limit.</p>


```csharp
public TraverseAssociationsDescription(TraversalDirection traversalDirection)
```
### TraverseAssociationsDescription(TraversalDirection, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsDescription.yml" sourcestartlinenumber="1">Initializes a new instance of <code>TraverseAssociationsDescription</code> with a full traversal in a specified <xref href="ArcGIS.Core.Data.UtilityNetwork.TraversalDirection" data-throw-if-not-resolved="false"></xref> with a user-defined depth limit.</p>


```csharp
public TraverseAssociationsDescription(TraversalDirection traversalDirection, int maximumDepth)
```
### AdditionalFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsDescription.yml" sourcestartlinenumber="1">Represents a list of field names to be included with the output of a traversal.</p>


```csharp
public List<string> AdditionalFields { get; set; }
```
### MaximumDepth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsDescription.yml" sourcestartlinenumber="1">The maximum number of hops through the association graph to traverse.</p>


```csharp
public int MaximumDepth { get; }
```
### TraversalDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TraverseAssociationsDescription.yml" sourcestartlinenumber="1">The direction of the traversal.</p>


```csharp
public TraversalDirection TraversalDirection { get; }
```


