# EventLog

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Utilities.html">Utilities</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Esri application event log class.</p>


## Object Signature

```csharp
public static class EventLog
```


## Members

### GetCounterNames()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Returns the names of all diagnostic counters.</p>


```csharp
public static string[] GetCounterNames()
```
### GetCounterValue(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Returns the current value of the specified diagnostic counter.</p>


```csharp
public static ulong GetCounterValue(string counterName)
```
### IncrementCounter(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Increments the specified diagnostic counter.</p>


```csharp
public static void IncrementCounter(string counterName)
```
### IsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Returns True if the application is running in diagnostic mode.</p>


```csharp
public static bool IsEnabled { get; }
```
### SetCounterValue(string, ulong)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Sets the value of the specified counter.</p>


```csharp
public static void SetCounterValue(string counterName, ulong value)
```
### ShouldLog(EventType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Used to control which types of events should be logged.</p>


```csharp
public static bool ShouldLog(EventLog.EventType type)
```
### Write(EventType, string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Creates a timestamped event record of the specified type.
Event is flushed immediately to disk if flush is set to true.</p>
<param name="type">The type of event to log.<param name="entry">User defined entry describing the event.<param name="flush">If true, event is written to disk immediately.


```csharp
public static void Write(EventLog.EventType type, string entry, bool flush = false)
```
### Write(EventType, string, string, string, uint, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Creates a timestamped event record of the specified type.
Event is flushed immediately to disk if flush is set to true.</p>
<param name="type">The type of event to log.<param name="entry">User defined entry describing the event.<param name="func">The function associated with the event.<param name="code">The code associated with the event.<param name="elapsed">The duration (in milliseconds) associated with the event.<param name="flush">If true, event is written to disk immediately.


```csharp
public static void Write(EventLog.EventType type, string entry, string func, string code, uint elapsed = 0, bool flush = false)
```
### Write(EventType, string, uint, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Creates a timestamped event record of the specified type.
Event is flushed immediately to disk if flush is set to true.</p>
<param name="type">The type of event to log.<param name="entry">User defined entry describing the event.<param name="elapsed">The duration (in milliseconds) associated with the event.<param name="flush">If true, event is written to disk immediately.


```csharp
public static void Write(EventLog.EventType type, string entry, uint elapsed, bool flush = false)
```
### Write(EventType, (string, string)[], string, string, uint, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Creates a timestamped event record of the specified type.
Event is flushed immediately to disk if flush is set to true.</p>
<param name="type">The type of event to log.<param name="customEventData">An array of tuples containing event name + value pairs.<param name="func">The function associated with the event.<param name="code">The code associated with the event.<param name="elapsed">The duration (in milliseconds) associated with the event.<param name="flush">If true, event is written to disk immediately.


```csharp
public static void Write(EventLog.EventType type, (string, string)[] customEventData, string func, string code, uint elapsed = 0, bool flush = false)
```
### Write(EventType, (string, string)[], uint, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.EventLog.yml" sourcestartlinenumber="1">Creates a timestamped event record of the specified type.
Event is flushed immediately to disk if flush is set to true.</p>
<param name="type">The type of event to log.<param name="customEventData">An array of tuples containing event name + value pairs.<param name="elapsed">The duration (in milliseconds) associated with the event.<param name="flush">If true, event is written to disk immediately.


```csharp
public static void Write(EventLog.EventType type, (string, string)[] customEventData, uint elapsed = 0, bool flush = false)
```


