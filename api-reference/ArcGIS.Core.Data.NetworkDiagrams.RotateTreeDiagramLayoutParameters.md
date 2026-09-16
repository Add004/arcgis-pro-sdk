# RotateTreeDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RotateTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Rotate Tree diagram layout parameters. This layout algorithm rotates the tree or trees related to pivot junctions currently set up in a diagram to the specified angle.</p>


## Object Signature

```csharp
public sealed class RotateTreeDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<ul>
  <li>
    This layout algorithm rotates the tree or trees related to the pivot junctions currently set up in the input network diagram layer according to the specified angle.
    </li>
  <li>
    The Rotate Tree algorithm requires at least one pivot junction, such as a junction used as the center point around which the related graph will be rotated. 
    The Rotate Tree layout also takes into account any barriers in the input diagram layer to prevent the algorithm from executing beyond the barriers.
    </li>
</ul>


## Members

### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RotateTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```
### RotateJunction

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RotateTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the junctions rotation field is updated.</p>


```csharp
public bool RotateJunction { get; set; }
```
### Rotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RotateTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Angle in degrees that will be used to rotate the tree.</p>


```csharp
public double Rotation { get; set; }
```


