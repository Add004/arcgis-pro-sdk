# RealtimeCursorBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursorBase.yml" sourcestartlinenumber="1">Abstract class for common functionality for a real-time cursor.  See <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursor" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class RealtimeCursorBase : CoreObjectsBase, IDisposable
```


## Members

### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursorBase.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method can be called on any thread.</p>


```csharp
public int FindField(string fieldName)
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursorBase.yml" sourcestartlinenumber="1">Gets the readonly list of <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>s present in the cursor.
This method can be called on any thread.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### GetState()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursorBase.yml" sourcestartlinenumber="1">Gets the state of this real-time cursor.
This method can be called on any thread.</p>


```csharp
public RealtimeCursorState GetState()
```
### Unsubscribe()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursorBase.yml" sourcestartlinenumber="1">Unsubscribes this real-time cursor from the <xref href="ArcGIS.Core.Data.Realtime.RealtimeTable" data-throw-if-not-resolved="false"></xref> events.
This method can be called on any thread.</p>


```csharp
public void Unsubscribe()
```
### WaitForRowsAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursorBase.yml" sourcestartlinenumber="1">Asynchronously waits for new rows to be available in the internal queue of this real-time cursor.
The returned <xref href="System.Threading.Tasks.Task" data-throw-if-not-resolved="false"></xref> will also complete if the state of this <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursor" data-throw-if-not-resolved="false"></xref> (see <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursorBase.GetState" data-throw-if-not-resolved="false"></xref>) changes from <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursorState.Subscribed" data-throw-if-not-resolved="false"></xref>.
This method can be called on any thread.</p>


```csharp
public Task<bool> WaitForRowsAsync()
```
### WaitForRowsAsync(CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursorBase.yml" sourcestartlinenumber="1">Asynchronously waits for new rows to be available in the internal queue of this real-time cursor.
The returned <xref href="System.Threading.Tasks.Task" data-throw-if-not-resolved="false"></xref> will also complete if the state of this <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursor" data-throw-if-not-resolved="false"></xref> (see <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursorBase.GetState" data-throw-if-not-resolved="false"></xref>) changes from <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursorState.Subscribed" data-throw-if-not-resolved="false"></xref>.
This method can be called on any thread.</p>


```csharp
public Task<bool> WaitForRowsAsync(CancellationToken cancellationToken)
```


