# AssociationFeature

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationFeature.yml" sourcestartlinenumber="1">Represents a connectivity, containment, or structural attachment association, including a <xref href="ArcGIS.Core.Geometry.Geometry" data-throw-if-not-resolved="false"></xref> representing a connection between the two rows involved in the association.</p>


## Object Signature

```csharp
public sealed class AssociationFeature : Association, IEquatable<Association>
```


## Members

### Equals(Association)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationFeature.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(Association other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationFeature.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationFeature.yml" sourcestartlinenumber="1">Obtains a hash code of the object.  Used in Equals.</p>


```csharp
public override int GetHashCode()
```
### Shape

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssociationFeature.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.Geometry" data-throw-if-not-resolved="false"></xref> that represents a connection between the two rows involved in the association.</p>


```csharp
public Geometry Shape { get; }
```


