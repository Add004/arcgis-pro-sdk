# DisplayOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DisplayOptions.yml" sourcestartlinenumber="1">Gets and sets the application display options.</p>


## Object Signature

```csharp
public class DisplayOptions
```


## Members

### ClearCacheWhenAppClosing

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DisplayOptions.yml" sourcestartlinenumber="1">Gets and sets whether the display cache will be cleared
automatically when the Pro application is closed.</p>


```csharp
public bool ClearCacheWhenAppClosing { get; set; }
```
### ClearDisplayCacheAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DisplayOptions.yml" sourcestartlinenumber="1">Clears the display cache from the local storage.
This method will close and reopen any project currently opened in order to clear the local storage.
The project should not have any unsaved change when the method is called. If it does, the call
will be a no-op.</p>


```csharp
public Task ClearDisplayCacheAsync()
```


