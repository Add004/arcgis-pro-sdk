# LayoutEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEventArgs.yml" sourcestartlinenumber="1">Provides the data for the <xref href="ArcGIS.Desktop.Layouts.Events.LayoutEvent?text=LayoutEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LayoutEventArgs : EventArgs
```


## Members

### Hint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEventArgs.yml" sourcestartlinenumber="1">Gets the layout event hint for this event</p>


```csharp
public LayoutEventHint Hint { get; }
```
### Layout

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEventArgs.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout+" data-throw-if-not-resolved="false"></xref> that was changed.</p>


```csharp
public Layout Layout { get; }
```
### OldPage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEventArgs.yml" sourcestartlinenumber="1">Gets the original layout <xref href="ArcGIS.Core.CIM.CIMPage" data-throw-if-not-resolved="false"></xref></p>


```csharp
public CIMPage OldPage { get; }
```


