# IANATimeZoneManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Class providing methods for interacting with IANA time zones.   See <xref href="ArcGIS.Desktop.Core.ProApp.IANATimeZoneManager" data-throw-if-not-resolved="false"></xref>.
For time zone information see <xref href="ArcGIS.Desktop.Framework.IANATimeZoneData" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class IANATimeZoneManager
```


## Members

### GetEmptyTimeZone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Gets the &quot;Empty&quot; time zone.</p>


```csharp
public IANATimeZoneData GetEmptyTimeZone()
```
### GetIanaIDFromWindowsID(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Gets the IANA time zone ID that is a close match to the specified windows time zone ID.</p>


```csharp
public static string GetIanaIDFromWindowsID(string windowsID, bool respectDST = true)
```
### GetLocalTimeZone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Gets the local time zone.</p>


```csharp
public IANATimeZoneData GetLocalTimeZone()
```
### GetSystemTimeZone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Gets the &quot;System&quot; time zone.  This time zone will use the local time zone on whatever system it's running on.</p>


```csharp
public IANATimeZoneData GetSystemTimeZone()
```
### GetTimeZoneByID(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Gets the time zone data for the specified time zone ID.</p>


```csharp
public IANATimeZoneData GetTimeZoneByID(string timeZoneID)
```
### GetTimeZones(bool, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Gets the list of time zones available on the system.</p>


```csharp
public IReadOnlyList<IANATimeZoneData> GetTimeZones(bool includeLocalTimeZone = true, bool includeUnknownTimeZone = false, bool includeEmptyTimeZone = false)
```
### GetUnknownTimeZone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Gets the &quot;Unknown&quot; time zone.</p>


```csharp
public IANATimeZoneData GetUnknownTimeZone()
```
### GetWindowsIDFromIanaID(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Gets the windows time zone ID that is a close match to the specified IANA time zone ID.</p>


```csharp
public static string GetWindowsIDFromIanaID(string ianaID)
```
### HasDefaultDstOffset(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Identifies if the specified time zone ID has a default daylight savings offset.</p>


```csharp
public static bool HasDefaultDstOffset(string timeZoneID)
```
### IsIanaID(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Identifies if the specified time zone ID is an IANA time zone ID.</p>


```csharp
public static bool IsIanaID(string timeZoneID)
```
### IsWindowsID(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IANATimeZoneManager.yml" sourcestartlinenumber="1">Identifies if the specified time zone ID is a windows time zone ID.</p>


```csharp
public static bool IsWindowsID(string timeZoneID)
```


