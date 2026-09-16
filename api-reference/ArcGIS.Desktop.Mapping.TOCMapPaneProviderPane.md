# TOCMapPaneProviderPane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Derive from TOCMapPaneProviderPane to impersonate a MapPane. When impersonating, the
pane will show the impersonated map pane's TOC and will close automatically when the
impersonated map pane is closed.</p>


## Object Signature

```csharp
public abstract class TOCMapPaneProviderPane : TOCActiveMapViewProviderPane, IContentsProvider, IMapPane
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">The impersonated map pane's ribbon (i.e. &quot;tabs&quot;) are also shown on the ribbon.</p>


## Members

### TOCMapPaneProviderPane(CIMView)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Constructor - provide the CIMView instance associated with this pane</p>


```csharp
public TOCMapPaneProviderPane(CIMView cimView)
```
### DockUnderMapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Gets whether the pane should be docked under the active map view
when opened</p>


```csharp
public virtual bool DockUnderMapView { get; }
```
### InitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Initializes the pane as part of its creation sequence.</p>


```csharp
protected override Task InitializeAsync()
```
### OnClosed()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Notification letting the Pane know it has been closed.</p>


```csharp
protected override void OnClosed()
```
### OnHidden()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Notification letting the Pane know it has been hidden.</p>


```csharp
protected override void OnHidden()
```
### OnNoActiveMapView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Called the impersonated map pane is closed</p>


```csharp
protected override void OnNoActiveMapView()
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Gets the OperationsManager associated with the Pane</p>


```csharp
public override OperationManager OperationManager { get; }
```
### Secondary

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Gets the secondary flag value. Returns true if the pane
can be positioned as a secondary pane &quot;under&quot; a Map View.</p>


```csharp
public override sealed bool Secondary { get; }
```
### _dockUnderMapView

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCMapPaneProviderPane.yml" sourcestartlinenumber="1">Derive from TOCMapPaneProviderPane to impersonate a MapPane. When impersonating, the
pane will show the impersonated map pane's TOC and will close automatically when the
impersonated map pane is closed.</p>


```csharp
protected bool _dockUnderMapView
```


