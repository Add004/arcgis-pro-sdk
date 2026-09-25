# TimeZoneConversion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeZoneConversion.yml" sourcestartlinenumber="1">Allows dates to be converted between two <xref href="ArcGIS.Core.CIM.TimeReference" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public static class TimeZoneConversion
```


## Members

### ConvertDateTime(DateTime, TimeReference, TimeReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeZoneConversion.yml" sourcestartlinenumber="1">Converts a <xref href="System.DateTime" data-throw-if-not-resolved="false"></xref> from one time zone to another.</p>


```csharp
public static DateTime ConvertDateTime(DateTime date, TimeReference fromTimeReference, TimeReference toTimeReference)
```
### GetFieldTimeZone(MapMember, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeZoneConversion.yml" sourcestartlinenumber="1">Get the time zone for a specific field of a <xref href="ArcGIS.Desktop.Mapping.MapMember" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static TimeReference GetFieldTimeZone(this MapMember mapMember, string fieldName)
```
### GetMapDisplayTimeZone(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeZoneConversion.yml" sourcestartlinenumber="1">Get the display time zone for a <xref href="ArcGIS.Desktop.Mapping.Map" data-throw-if-not-resolved="false"></xref>. Returns null when the map's time zone is not used for displaying data values.</p>


```csharp
public static TimeReference GetMapDisplayTimeZone(this Map map)
```


