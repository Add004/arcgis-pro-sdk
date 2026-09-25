# Association

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Represents a connectivity (spatial and non-spatial), containment, or structural attachment association.</p>


## Object Signature

```csharp
public class Association : IEquatable<Association>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Association objects are not reflected in the topological index if they have not yet been validated with <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.ValidateNetworkTopology" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Association(AssociationType, Element, Element)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>Association</code> class.</p>


```csharp
public Association(AssociationType type, Element fromElement, Element toElement)
```
### Association(AssociationType, Element, Element, ContainmentVisibility)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>Association</code> class.  Use this overload if <code class="paramref">type</code> is
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Containment" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Association(AssociationType type, Element containerElement, Element contentElement, ContainmentVisibility containmentVisibility)
```
### Association(AssociationType, Element, Element, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>Association</code> class.  Use this overload if <code class="paramref">type</code> is
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityMidspan" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityFromSide" data-throw-if-not-resolved="false"></xref>
or <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityToSide" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Association(AssociationType type, Element junction, Element edgeObject, double percentAlong)
```
### Equals(Association)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public virtual bool Equals(Association other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### FromElement

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Represents the first participant in an Association.</p>


```csharp
public Element FromElement { get; }
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Obtains a hash code of the object.  Used in Equals.</p>


```csharp
public override int GetHashCode()
```
### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Gets the GlobalID of this <code>Association</code>.</p>


```csharp
public Guid GlobalID { get; }
```
### IsContainmentVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Gets a value indicating whether the content is visible if this <code>Association</code> represents a
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Containment" data-throw-if-not-resolved="false"></xref> association.</p>


```csharp
public bool IsContainmentVisible { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Gets the ObjectID of this <code>Association</code>.</p>


```csharp
public long ObjectID { get; }
```
### PercentAlong

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Gets the percent along the mid span of a non-spatial edge object that a junction or non-spatial junction object
is connected to if this <code>Association</code> represents a
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityMidspan" data-throw-if-not-resolved="false"></xref> association.</p>


```csharp
public double PercentAlong { get; }
```
### ToElement

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Represents the second participant in an Association.</p>


```csharp
public Element ToElement { get; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType" data-throw-if-not-resolved="false"></xref> that this Association represents.</p>


```csharp
public AssociationType Type { get; }
```
### operator ==(Association, Association)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">association1</code> and <code class="paramref">association2</code> are equal.</p>


```csharp
public static bool operator ==(Association association1, Association association2)
```
### operator !=(Association, Association)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Association.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">association1</code> and <code class="paramref">association2</code> are not equal.</p>


```csharp
public static bool operator !=(Association association1, Association association2)
```


