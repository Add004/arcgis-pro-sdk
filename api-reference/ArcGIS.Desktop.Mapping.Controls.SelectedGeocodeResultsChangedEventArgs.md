# SelectedGeocodeResultsChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SelectedGeocodeResultsChangedEventArgs.yml" sourcestartlinenumber="1">Passed as the event parameter in the SelectedGeocodeResultsChanged event.</p>


## Object Signature

```csharp
public class SelectedGeocodeResultsChangedEventArgs : EventArgs
```


## Members

### GeocodeResults

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SelectedGeocodeResultsChangedEventArgs.yml" sourcestartlinenumber="1">Gets the set of selected <xref href="ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult" data-throw-if-not-resolved="false"></xref> objects in the <xref href="ArcGIS.Desktop.Mapping.Controls.LocatorControl" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<GeocodeResult> GeocodeResults { get; }
```


