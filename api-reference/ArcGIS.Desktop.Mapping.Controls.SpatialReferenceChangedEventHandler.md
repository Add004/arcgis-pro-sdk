# SpatialReferenceChangedEventHandler

- Type: delegate
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SpatialReferenceChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SpatialReferenceChanged event of the CoordinateSystemsControl</p>


## Object Signature

```csharp
public delegate void SpatialReferenceChangedEventHandler(object sender, SpatialReferenceChangedEventArgs args)
```


## Members

### SpatialReferenceChangedEventHandler(object, nint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SpatialReferenceChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SpatialReferenceChanged event of the CoordinateSystemsControl</p>


```csharp
public SpatialReferenceChangedEventHandler(object @object, nint method)
```
### BeginInvoke(object, SpatialReferenceChangedEventArgs, AsyncCallback, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SpatialReferenceChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SpatialReferenceChanged event of the CoordinateSystemsControl</p>


```csharp
public virtual IAsyncResult BeginInvoke(object sender, SpatialReferenceChangedEventArgs args, AsyncCallback callback, object @object)
```
### EndInvoke(IAsyncResult)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SpatialReferenceChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SpatialReferenceChanged event of the CoordinateSystemsControl</p>


```csharp
public virtual void EndInvoke(IAsyncResult result)
```
### Invoke(object, SpatialReferenceChangedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SpatialReferenceChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SpatialReferenceChanged event of the CoordinateSystemsControl</p>


```csharp
public virtual void Invoke(object sender, SpatialReferenceChangedEventArgs args)
```


