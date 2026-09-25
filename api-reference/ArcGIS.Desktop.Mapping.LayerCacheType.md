# LayerCacheType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCacheType.yml" sourcestartlinenumber="1">Layer cache type.  Use with <xref href="ArcGIS.Desktop.Mapping.Layer.SetCacheOptions(ArcGIS.Desktop.Mapping.LayerCacheType)" data-throw-if-not-resolved="false"></xref> to control layer caching options.</p>


## Object Signature

```csharp
public enum LayerCacheType
```


## Members

### MaxAge

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCacheType.yml" sourcestartlinenumber="1">Cache will be kept between sessions and cleared every <xref href="ArcGIS.Desktop.Mapping.Layer.MaxDisplayCacheAge" data-throw-if-not-resolved="false"></xref> minutes.
Use <xref href="ArcGIS.Desktop.Mapping.Layer.SetDisplayCacheMaxAge(System.TimeSpan)?text=SetDisplayCacheMaxAge" data-throw-if-not-resolved="false"></xref> to set the cache age.
Not supported for layers that support feature caching (i.e. feature service layers).</p>


```csharp
MaxAge = 2
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCacheType.yml" sourcestartlinenumber="1">Don't cache the layer locally.
If the layer supports feature caching (i.e. is a feature service layer), then any existing cache is also cleared.</p>


```csharp
None = 0
```
### Permanent

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCacheType.yml" sourcestartlinenumber="1">Cache will be kept between sessions and invalidated when the data is updated.
Not supported for layers that support feature caching (i.e. feature service layers).</p>


```csharp
Permanent = 3
```
### Session

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCacheType.yml" sourcestartlinenumber="1">Cache will be cleared when the session ends.</p>


```csharp
Session = 1
```


