# TOCActiveMapViewProviderPane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Derive from TOCActiveMapViewProviderPane to continue to show the TOC of
an associated MapView when your (derived) pane is activated. The MapView
with the relevant TOC should be set in your Initialize override via the
SetMapUri instance method.</p>


## Object Signature

```csharp
public abstract class TOCActiveMapViewProviderPane : ViewStatePane, IContentsProvider
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Typically, consumers will derive from <xref href="ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane" data-throw-if-not-resolved="false"></xref> instead which
provides full impersonation of a MapPane and its associated MapView.</p>
<p></p>
<pre><code sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="5">        If you do use TOCActiveMapViewProviderPane then your derived class is responsible for handling
        any enabled state change, visibility change, etc. relevant to the MapView, whose TOC you are showing,
        being closed
</code></pre>


## Members

### TOCActiveMapViewProviderPane(CIMView)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Constructor - provide a CIMView instance. Note: The CIMView will be persisted in the
project when the project is saved.</p>


```csharp
public TOCActiveMapViewProviderPane(CIMView cimView)
```
### InitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Called when the pane is initialized (when it is created). Derived classes must call
the base.InitializeAsync() if they override it.</p>


```csharp
protected override Task InitializeAsync()
```
### IsClosed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Gets a flag indicating if this pane has been closed.</p>


```csharp
public bool IsClosed { get; protected set; }
```
### IsHidden

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Gets a flag indicating if this pane has been hidden.</p>


```csharp
public bool IsHidden { get; protected set; }
```
### MapURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Gets the Map URI (of the MapView) associated with this pane</p>


```csharp
public string MapURI { get; }
```
### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Gets and sets the MapView whose TOC is associated with this pane</p>


```csharp
public MapView MapView { get; set; }
```
### OnActivate(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Called when the pane is activated (receives focus - active is true) or
deactivated (loses focus - active is false).</p>


```csharp
protected override void OnActivate(bool active)
```
### OnActiveMapViewChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Override to implement special behavior when the active map view is changed.</p>


```csharp
protected virtual void OnActiveMapViewChanged()
```
### OnClosed()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Called when the pane is closed</p>


```csharp
protected override void OnClosed()
```
### OnHidden()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Called when the pane is hidden</p>


```csharp
protected override void OnHidden()
```
### OnNoActiveMapView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Override to implement special behavior when the associated map view is closed</p>


```csharp
protected virtual void OnNoActiveMapView()
```
### SetMapURI(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Sets the Map URI of the MapView whose TOC is to be shown when this pane is
activated</p>


```csharp
public Task SetMapURI(string mapURI)
```
### UninitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCActiveMapViewProviderPane.yml" sourcestartlinenumber="1">Called when the pane is uninitialized.</p>


```csharp
protected override Task UninitializeAsync()
```


