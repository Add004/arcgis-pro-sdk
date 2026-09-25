# TimeRange

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Represents an extent of time defined by a start and an end time.</p>


## Object Signature

```csharp
public class TimeRange
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">TimeRange contains two properties <xref href="ArcGIS.Desktop.Mapping.TimeRange.Start" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.TimeRange.End" data-throw-if-not-resolved="false"></xref> which defines an extent of time. Either property can be set to null.
When <xref href="ArcGIS.Desktop.Mapping.TimeRange.Start" data-throw-if-not-resolved="false"></xref> is null it means the time range begins infinite in the past and when <xref href="ArcGIS.Desktop.Mapping.TimeRange.End" data-throw-if-not-resolved="false"></xref> is null this means it ends infinite
in the future. This is useful for example when setting the <xref href="ArcGIS.Desktop.Mapping.MapView.Time" data-throw-if-not-resolved="false"></xref> property to show all time before a
given date, all time after a given date or to just show all time.</p>


## Members

### TimeRange()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Initialize a new instance of a TimeRange.</p>


```csharp
public TimeRange()
```
### TimeRange(DateTime, TimeDelta)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Initialize a new instance of a TimeRange using a date and a time interval.</p>


```csharp
public TimeRange(DateTime dateTime, TimeDelta timeDelta)
```
### TimeRange(DateTime, TimeDelta, TimeReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Initialize a new instance of a TimeRange using a date and a time interval.</p>


```csharp
public TimeRange(DateTime dateTime, TimeDelta timeDelta, TimeReference timeReference)
```
### TimeRange(DateTime, DateTime)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Initialize a new instance of a TimeRange using a start and end time.</p>


```csharp
public TimeRange(DateTime start, DateTime end)
```
### TimeRange(DateTime, DateTime, TimeReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Initialize a new instance of a TimeRange using a start and end time.</p>


```csharp
public TimeRange(DateTime start, DateTime end, TimeReference timeReference)
```
### End

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Gets or sets the end time for the range.</p>


```csharp
public DateTime? End { get; set; }
```
### Equals(TimeRange)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Determines whether the specified TimeRange is equivalent to the current TimeRange.</p>


```csharp
public bool Equals(TimeRange range)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Determines whether the specified TimeRange is equivalent to the current TimeRange.</p>


```csharp
public override bool Equals(object obj)
```
### ExcludeEnd

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Gets or sets whether times equal to the end time are considered matches.</p>


```csharp
public bool ExcludeEnd { get; set; }
```
### ExcludeStart

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Gets or sets whether times equal to the start time are considered matches.</p>


```csharp
public bool ExcludeStart { get; set; }
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Serves as the default hash function.</p>


```csharp
public override int GetHashCode()
```
### Intersects(TimeRange)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Checks if this instance intersects the specified time range.</p>


```csharp
public bool Intersects(TimeRange timeRange)
```
### Intersects(DateTime)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Checks if this instance intersects the specified date.</p>


```csharp
public bool Intersects(DateTime dateTime)
```
### Offset(TimeDelta)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Returns a new time range offset from the current instance using the specified time interval.</p>


```csharp
public TimeRange Offset(TimeDelta timeDelta)
```
### Start

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Gets or sets the start time for the range.</p>


```csharp
public DateTime? Start { get; set; }
```
### TimeReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeRange.yml" sourcestartlinenumber="1">Gets or sets the time reference for the range.</p>


```csharp
public TimeReference TimeReference { get; set; }
```


