# IContentsControl

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsControl.yml" sourcestartlinenumber="1">Implement this interface on the View Model associated with your Contents control to
override the default Contents caption or make your control read-only.</p>


## Object Signature

```csharp
public interface IContentsControl
```


## Members

### CaptionOverride

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsControl.yml" sourcestartlinenumber="1">Gets the default caption to be used for the Contents dock pane.</p>


```csharp
string CaptionOverride { get; }
```
### ReadOnly

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsControl.yml" sourcestartlinenumber="1">Gets whether the control is in a read-only state.</p>


```csharp
bool ReadOnly { get; set; }
```


