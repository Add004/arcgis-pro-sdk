# RangeDomain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Attributes.html">Attributes</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.RangeDomain.yml" sourcestartlinenumber="1">Represents a range domain.</p>


## Object Signature

```csharp
public sealed class RangeDomain : Domain
```

## Remarks

<p>A range domain specifies a valid range of values for a numeric attribute. 
    A range domain can be applied to short-integer, long-integer, float, double, and date attribute types.</p>


## Members

### IsMemberOf(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.RangeDomain.yml" sourcestartlinenumber="1">Checks whether given value falls in the range.</p>


```csharp
public override bool IsMemberOf(object value)
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.RangeDomain.yml" sourcestartlinenumber="1">Gets the maximum value of this Range Domain.</p>


```csharp
public object Max { get; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.RangeDomain.yml" sourcestartlinenumber="1">Gets the minimum value of this Range Domain.</p>


```csharp
public object Min { get; }
```


