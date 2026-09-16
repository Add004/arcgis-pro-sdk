# TimeDelta

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeDelta.yml" sourcestartlinenumber="1">Represents a time interval defined by a positive or negative value and a unit of time.</p>


## Object Signature

```csharp
public class TimeDelta
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeDelta.yml" sourcestartlinenumber="1">Similar to <xref href="System.TimeSpan" data-throw-if-not-resolved="false"></xref> this class offers advantages in that it can represent time intervals that are not uniform in time,
for example months or years. <xref href="ArcGIS.Desktop.Mapping.TimeRange.Offset(ArcGIS.Desktop.Mapping.TimeDelta)" data-throw-if-not-resolved="false"></xref> and other members accepting TimeDelta as an input are able to account and handle
these irregular time periods like months or years when calculating new dates and times.</p>


## Members

### TimeDelta(double, TimeUnit)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeDelta.yml" sourcestartlinenumber="1">Initialize a new instance of a TimeDelta using a value and a time unit.</p>


```csharp
public TimeDelta(double value, TimeUnit timeUnit)
```
### TimeUnit

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeDelta.yml" sourcestartlinenumber="1">Gets or sets the unit of time.</p>


```csharp
public TimeUnit TimeUnit { get; set; }
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeDelta.yml" sourcestartlinenumber="1">Gets or sets the value.</p>


```csharp
public double Value { get; set; }
```


