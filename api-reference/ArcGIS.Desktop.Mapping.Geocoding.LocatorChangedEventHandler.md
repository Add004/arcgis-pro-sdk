# LocatorChangedEventHandler

- Type: delegate
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Geocoding.html">Geocoding</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the LocatorChanged event.</p>


## Object Signature

```csharp
public delegate void LocatorChangedEventHandler(object sender, LocatorChangedEventArgs args)
```


## Members

### LocatorChangedEventHandler(object, nint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the LocatorChanged event.</p>


```csharp
public LocatorChangedEventHandler(object @object, nint method)
```
### BeginInvoke(object, LocatorChangedEventArgs, AsyncCallback, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the LocatorChanged event.</p>


```csharp
public virtual IAsyncResult BeginInvoke(object sender, LocatorChangedEventArgs args, AsyncCallback callback, object @object)
```
### EndInvoke(IAsyncResult)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the LocatorChanged event.</p>


```csharp
public virtual void EndInvoke(IAsyncResult result)
```
### Invoke(object, LocatorChangedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the LocatorChanged event.</p>


```csharp
public virtual void Invoke(object sender, LocatorChangedEventArgs args)
```


