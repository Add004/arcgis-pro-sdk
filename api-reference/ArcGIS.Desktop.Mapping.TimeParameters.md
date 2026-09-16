# TimeParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Represents a set of properties for describing a time filter assigned to a <xref href="ArcGIS.Desktop.Mapping.MapMember" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class TimeParameters
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Achieve a fixed time extent filter by setting the <xref href="ArcGIS.Desktop.Mapping.TimeRange.Start" data-throw-if-not-resolved="false"></xref> and/or <xref href="ArcGIS.Desktop.Mapping.TimeRange.End" data-throw-if-not-resolved="false"></xref> properties.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="5">Achieve a time filter based on a single attribute field by setting the <xref href="ArcGIS.Desktop.Mapping.TimeParameters.StartTimeFieldName" data-throw-if-not-resolved="false"></xref> property.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="9">Achieve a time filter for data with both start and end times by setting the <xref href="ArcGIS.Desktop.Mapping.TimeParameters.StartTimeFieldName" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Desktop.Mapping.TimeParameters.EndTimeFieldName" data-throw-if-not-resolved="false"></xref> properties.</p>


## Members

### TimeParameters()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Represents a set of properties for describing a time filter assigned to a <xref href="ArcGIS.Desktop.Mapping.MapMember" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TimeParameters()
```
### EndTimeFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1"><remarks></remarks>
Gets and sets a second time field name.  Use this if features have both start and end times stored in two fields.</p>


```csharp
public string EndTimeFieldName { get; set; }
```
### GetSupportedTimeFormats(FieldType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets the supported time formats for the specified field type.</p>


```csharp
public List<string> GetSupportedTimeFormats(FieldType fieldType)
```
### IsCumulative

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets and sets if time is cumulative.  Default value is false.</p>


```csharp
public bool IsCumulative { get; set; }
```
### IsLiveFeed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets and set if time data includes continuous updates.</p>


```csharp
public bool IsLiveFeed { get; set; }
```
### IsValid()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets if the time parameters are valid.</p>


```csharp
public bool IsValid()
```
### StartTimeFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets and sets the time Field name. Use this if the time stamps are stored in a single attribute field.</p>


```csharp
public string StartTimeFieldName { get; set; }
```
### StepInterval

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets and sets the step interval.   Use this when <xref href="ArcGIS.Desktop.Mapping.TimeParameters.TimeIntervalType" data-throw-if-not-resolved="false"></xref> = <xref href="ArcGIS.Desktop.Mapping.TimeIntervalType.Regular" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TimeDelta StepInterval { get; set; }
```
### TimeFormat

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets and sets the time format for the data.</p>


```csharp
public string TimeFormat { get; set; }
```
### TimeIntervalType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets and sets the type of time internval.  Default is <xref href="ArcGIS.Desktop.Mapping.TimeIntervalType.None" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TimeIntervalType TimeIntervalType { get; set; }
```
### TimeOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets and sets the time offset.  Default is to have no time offset; ie null.</p>


```csharp
public TimeDelta TimeOffset { get; set; }
```
### TimeRange

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeParameters.yml" sourcestartlinenumber="1">Gets and sets the time extent. This consists of a <xref href="ArcGIS.Desktop.Mapping.TimeRange.Start" data-throw-if-not-resolved="false"></xref> date and an <xref href="ArcGIS.Desktop.Mapping.TimeRange.End" data-throw-if-not-resolved="false"></xref> date.
If specifying a fixed time extent filter for a mapMember, then either of the start or end dates can remain
unspecified to achieve a period where the data will be displayed infinitely in the direction where there is no
time value.</p>


```csharp
public TimeRange TimeRange { get; set; }
```


