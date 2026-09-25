# Element

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Represents a row inside a utility network.</p>


## Object Signature

```csharp
public class Element : IEquatable<Element>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">The Element class is used to represent a row inside a utility network.</p>
<ul><li>If the row represents a junction with terminals, Element can also specify a terminal. </li><li>If the row represents a line to be used as a tracing starting point or barrier, the percent along the edge can be specified to specify an exact location.</li></ul>
<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="5">Elements can be created using the CreateElement factory methods on the <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork" data-throw-if-not-resolved="false"></xref> class and can be returned with trace results.</p>


## Members

### AssetGroup

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetGroup" data-throw-if-not-resolved="false"></xref> of the Row represented by the Element.</p>


```csharp
public AssetGroup AssetGroup { get; }
```
### AssetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> of the Row represented by the Element.</p>


```csharp
public AssetType AssetType { get; }
```
### Equals(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public bool Equals(Element other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Obtains a hash code of the object.  Used in Equals.</p>


```csharp
public override int GetHashCode()
```
### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Gets the GlobalID of the Row represented by the Element.</p>


```csharp
public Guid GlobalID { get; }
```
### NetworkSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkSource" data-throw-if-not-resolved="false"></xref> (usually a table) that stores the Row represented by the Element.</p>


```csharp
public NetworkSource NetworkSource { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Gets the ObjectID of the Row represented by the Element.</p>


```csharp
public long ObjectID { get; }
```
### PercentAlongEdge

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">If this Element represents an edge feature, this may be used to specify the exact point along the edge.</p>


```csharp
public double PercentAlongEdge { get; set; }
```
### PositionFrom

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Indicates where on the linear feature the edge element starts, represented as a percentage of the length of the feature (between 0 and 1).</p>


```csharp
public double PositionFrom { get; }
```
### PositionTo

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Indicates where on the linear feature the edge element ends, represented as a percentage of the length of the feature (between 0 and 1)</p>


```csharp
public double PositionTo { get; }
```
### Terminal

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Gets or sets The <xref href="ArcGIS.Core.Data.UtilityNetwork.Terminal" data-throw-if-not-resolved="false"></xref> of the Row represented by the Element.</p>


```csharp
public Terminal Terminal { get; set; }
```
### operator ==(Element, Element)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">thisElement</code> and <code class="paramref">otherElement</code> are equal.</p>


```csharp
public static bool operator ==(Element thisElement, Element otherElement)
```
### operator !=(Element, Element)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Element.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">thisElement</code> and <code class="paramref">otherElement</code> are not equal.</p>


```csharp
public static bool operator !=(Element thisElement, Element otherElement)
```


