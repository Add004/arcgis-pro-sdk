# LocatorManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Geocoding.html">Geocoding</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.yml" sourcestartlinenumber="1">Class representing the locator providers available for the specified map.</p>


## Object Signature

```csharp
public sealed class LocatorManager
```


## Members

### AddLocatorAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.yml" sourcestartlinenumber="1">Add a locator to the set of available locators.</p>


```csharp
public Task<LocatorProvider> AddLocatorAsync(string providerPath)
```
### GeocodeAsync(string, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.yml" sourcestartlinenumber="1">Perform a geocode operation.  Geocode results are returned according to the active locator providers.</p>


```csharp
public Task<IList<GeocodeResult>> GeocodeAsync(string location, bool showResultsOnMap, bool zoomToFirstResult)
```
### GeocodeAsync(string, bool, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.yml" sourcestartlinenumber="1">Perform a geocode operation.  Geocode results are returned according to the active locator providers.</p>


```csharp
public Task<IList<GeocodeResult>> GeocodeAsync(string location, bool showResultsOnMap, bool zoomToFirstResult, bool showCancelPrompt)
```
### GetLocatorInformationAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.yml" sourcestartlinenumber="1">Gets a snapshot of the current locator provider information.</p>


```csharp
public Task<IList<LocatorProvider>> GetLocatorInformationAsync()
```
### LocatorChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.yml" sourcestartlinenumber="1">The LocatorChanged event is raised when the locator providers are altered.  A change consists of one of the following :
locators are addded, locators are removed, locator order changes or their UseSuggestions, Enable flags are altered.</p>


```csharp
public event LocatorChangedEventHandler LocatorChanged
```
### MoveLocatorAsync(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.yml" sourcestartlinenumber="1">Reorders the position of a locator.  Moves it up or down the provider list.</p>


```csharp
public Task MoveLocatorAsync(string providerName, int index)
```
### RemoveLocatorAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.yml" sourcestartlinenumber="1">Removes the specified locator.</p>


```csharp
public Task RemoveLocatorAsync(string providerPath)
```


