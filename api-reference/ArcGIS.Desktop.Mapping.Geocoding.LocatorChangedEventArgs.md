# LocatorChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Geocoding.html">Geocoding</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorChangedEventArgs.yml" sourcestartlinenumber="1">Passed as the event parameter in the LocatorChanged event.</p>


## Object Signature

```csharp
public sealed class LocatorChangedEventArgs : EventArgs
```


## Members

### LocatorChangedType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorChangedEventArgs.yml" sourcestartlinenumber="1">Gets the change which caused the LocatorChanged event to be thrown.</p>


```csharp
public LocatorChangedType LocatorChangedType { get; }
```
### LocatorProviderName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorChangedEventArgs.yml" sourcestartlinenumber="1">Gets the locator provider name.</p>


```csharp
public string LocatorProviderName { get; }
```


