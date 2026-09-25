# ViewStatePane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ViewStatePane.yml" sourcestartlinenumber="1">Represents a primary window within the application that persists its view state with the project. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class ViewStatePane : Pane
```


## Members

### ViewStatePane(CIMView)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.ViewStatePane.yml" sourcestartlinenumber="1">Initialize a new instance of a window</p>


```csharp
public ViewStatePane(CIMView cimView)
```
### ViewState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ViewStatePane.yml" sourcestartlinenumber="1">Gets the view state of the window</p>


```csharp
public abstract CIMView ViewState { get; }
```
### _cimView

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.ViewStatePane.yml" sourcestartlinenumber="1">The view state of the window</p>


```csharp
protected CIMView _cimView
```


