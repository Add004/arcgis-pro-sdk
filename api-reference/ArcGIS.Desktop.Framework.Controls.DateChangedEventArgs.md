# DateChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateChangedEventArgs.yml" sourcestartlinenumber="1">Passed as the event parameter in the SelectedDateChanged event for the DateTimePickerControl.</p>


## Object Signature

```csharp
public class DateChangedEventArgs : EventArgs
```


## Members

### DateTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateChangedEventArgs.yml" sourcestartlinenumber="1">Gets the date/time.</p>


```csharp
public DateTime? DateTime { get; }
```
### DateTimeOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateChangedEventArgs.yml" sourcestartlinenumber="1">Gets the date time offset.</p>


```csharp
public DateTimeOffset? DateTimeOffset { get; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateChangedEventArgs.yml" sourcestartlinenumber="1">Gets the date offset.</p>


```csharp
public TimeSpan? Offset { get; }
```


