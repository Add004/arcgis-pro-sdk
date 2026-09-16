# NetworkAttributeComparison

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.yml" sourcestartlinenumber="1">The NetworkAttributeComparison conditional expression performs a comparison against the value of a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref>.<br>
The comparison may be against a specific value or against a second <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.NetworkAttribute" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class NetworkAttributeComparison : ConditionalExpression
```


## Members

### NetworkAttributeComparison(NetworkAttribute, Operator, NetworkAttribute)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public NetworkAttributeComparison(NetworkAttribute networkAttribute, Operator comparisonOperator, NetworkAttribute otherNetworkAttribute)
```
### NetworkAttributeComparison(NetworkAttribute, Operator, object)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public NetworkAttributeComparison(NetworkAttribute networkAttribute, Operator comparisonOperator, object value)
```
### NetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> to use in the comparison.</p>


```csharp
public NetworkAttribute NetworkAttribute { get; }
```
### Operator

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.yml" sourcestartlinenumber="1">The operator to use in the comparison (equals, less than, etc.).</p>


```csharp
public Operator Operator { get; }
```
### OtherNetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.yml" sourcestartlinenumber="1">The second <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.NetworkAttribute" data-throw-if-not-resolved="false"></xref> that should be compared to the first. If this value was not set in the constructor, this property returns null.</p>


```csharp
public NetworkAttribute OtherNetworkAttribute { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.yml" sourcestartlinenumber="1">Gets a text representation of this object.</p>


```csharp
public override string ToString()
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NetworkAttributeComparison.yml" sourcestartlinenumber="1">The specific value to compare to the <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref>.  If this value was not set in the constructor, this property returns null.</p>


```csharp
public object Value { get; }
```


