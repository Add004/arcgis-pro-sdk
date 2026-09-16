# FeatureElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FeatureElement.yml" sourcestartlinenumber="1">Represents a row inside a utility network that is returned from a trace operation with the Features result type.</p>


## Object Signature

```csharp
public sealed class FeatureElement : Element, IEquatable<Element>
```


## Members

### ResultFieldValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FeatureElement.yml" sourcestartlinenumber="1">Gets the field values that were specified in the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.ResultOptions" data-throw-if-not-resolved="false"></xref> during a trace.</p>


```csharp
public IReadOnlyList<TraceResultFieldValue> ResultFieldValues { get; }
```
### ResultNetworkAttributeValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.FeatureElement.yml" sourcestartlinenumber="1">Gets the network attribute values that were specified in the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.ResultOptions" data-throw-if-not-resolved="false"></xref> during a trace.</p>


```csharp
public IReadOnlyList<TraceResultFieldValue> ResultNetworkAttributeValues { get; }
```


