# RangeDomain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RangeDomain.yml" sourcestartlinenumber="1">Represents the information about the valid coded values belonging to this coded value domain.</p>


## Object Signature

```csharp
public sealed class RangeDomain : Domain, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.RangeDomain.yml" sourcestartlinenumber="1">A RangeDomain maintains the information about the minimum and maximum valid values managed by this range domain.
Domains may be assigned to a field at the table level or if the table has subtypes they would be assigned at the subtype level.
A domain indicates the valid values for a field, and will indicate during validation if the field value is outside of this valid range.</p>


## Members

### GetMaxValue()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RangeDomain.yml" sourcestartlinenumber="1">Gets the maximum valid value in the domain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetMaxValue()
```
### GetMinValue()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RangeDomain.yml" sourcestartlinenumber="1">Gets the minimum valid value in the domain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetMinValue()
```


