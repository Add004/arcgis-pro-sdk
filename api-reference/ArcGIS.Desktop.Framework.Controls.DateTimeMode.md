# DateTimeMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimeMode.yml" sourcestartlinenumber="1">The mode in which the DateTimePickerControl should operate.  See <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.Mode" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum DateTimeMode
```


## Members

### DateOnly

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimeMode.yml" sourcestartlinenumber="1">Display as a date only control. Use this format with a field of type <xref href="ArcGIS.Core.Data.FieldType.DateOnly" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
DateOnly = 2
```
### DateTime

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimeMode.yml" sourcestartlinenumber="1">Display as a date time control.  Use this format with a field of type <xref href="ArcGIS.Core.Data.FieldType.Date" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
DateTime = 0
```
### DateTimeMS

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimeMode.yml" sourcestartlinenumber="1">Display as a date time control with milliseconds.  Use this format with a field of type <xref href="ArcGIS.Core.Data.FieldType.Date" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.Data.Field.Precision" data-throw-if-not-resolved="false"></xref> = 1 (high precision).</p>


```csharp
DateTimeMS = 1
```
### DateTimeOffset

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimeMode.yml" sourcestartlinenumber="1">Display as a date time with offset.  Use this format with a field of type <xref href="ArcGIS.Core.Data.FieldType.TimestampOffset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
DateTimeOffset = 4
```
### TimeOnly

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimeMode.yml" sourcestartlinenumber="1">Display as a time only control. Use this format with a field of type <xref href="ArcGIS.Core.Data.FieldType.TimeOnly" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
TimeOnly = 3
```


