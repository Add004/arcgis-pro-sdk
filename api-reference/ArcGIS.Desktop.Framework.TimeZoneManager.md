# TimeZoneManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.TimeZoneManager.yml" sourcestartlinenumber="1">Class providing methods for interacting with time zones.  See <xref href="ArcGIS.Desktop.Core.ProApp.TimeZoneManager" data-throw-if-not-resolved="false"></xref>.
For time zone information see <xref href="ArcGIS.Desktop.Framework.TimeZoneData" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class TimeZoneManager
```


## Members

### GetEmptyTimeZone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.TimeZoneManager.yml" sourcestartlinenumber="1">Gets the &quot;Empty&quot; time zone.</p>


```csharp
public TimeZoneData GetEmptyTimeZone()
```
### GetLocalTimeZone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.TimeZoneManager.yml" sourcestartlinenumber="1">Gets the local time zone.</p>


```csharp
public TimeZoneData GetLocalTimeZone()
```
### GetSystemTimeZone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.TimeZoneManager.yml" sourcestartlinenumber="1">Gets the &quot;System&quot; time zone.  This time zone will use the local time zone on whatever system it's running on.</p>


```csharp
public TimeZoneData GetSystemTimeZone()
```
### GetTimeZoneByID(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.TimeZoneManager.yml" sourcestartlinenumber="1">Gets the time zone data for the specified time zone ID.</p>


```csharp
public TimeZoneData GetTimeZoneByID(string timeZoneID)
```
### GetTimeZones(bool, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.TimeZoneManager.yml" sourcestartlinenumber="1">Gets the list of time zones available on the system.</p>


```csharp
public IReadOnlyList<TimeZoneData> GetTimeZones(bool includeLocalTimeZone = true, bool includeUnknownTimeZone = false, bool includeEmptyTimeZone = false)
```
### GetUnknownTimeZone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.TimeZoneManager.yml" sourcestartlinenumber="1">Gets the &quot;Unknown&quot; time zone.</p>


```csharp
public TimeZoneData GetUnknownTimeZone()
```


