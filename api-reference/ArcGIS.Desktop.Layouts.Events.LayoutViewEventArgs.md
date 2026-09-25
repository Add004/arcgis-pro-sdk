# LayoutViewEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutViewEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Layouts.Events.LayoutViewEvent?text=LayoutViewEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LayoutViewEventArgs : EventArgs
```


## Members

### Cancel

- Kind: property


```csharp
public bool Cancel { get; set; }
```
### DrawingPaused

- Kind: property


```csharp
public bool DrawingPaused { get; }
```
### Hint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutViewEventArgs.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Layouts.Events.LayoutViewEventHint?text=LayoutViewEventHint+type" data-throw-if-not-resolved="false"></xref> of event.</p>


```csharp
public LayoutViewEventHint Hint { get; }
```
### LayoutView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutViewEventArgs.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Layouts.LayoutView?text=LayoutView" data-throw-if-not-resolved="false"></xref> that is associated with the event.</p>


```csharp
public LayoutView LayoutView { get; }
```


