# LocatorProvider

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Geocoding.html">Geocoding</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorProvider.yml" sourcestartlinenumber="1">Class that provides information about locator providers.</p>


## Object Signature

```csharp
public sealed class LocatorProvider
```


## Members

### ActivateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorProvider.yml" sourcestartlinenumber="1">Activates the locator provider; that is ensures that UseProvider is true if the locator is valid.</p>


```csharp
public Task ActivateAsync()
```
### DeactivateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorProvider.yml" sourcestartlinenumber="1">Deactivates the locator provider; that is ensures that UseProvider is false if the locator is valid.</p>


```csharp
public Task DeactivateAsync()
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorProvider.yml" sourcestartlinenumber="1">Gets whether the locator provider is valid.</p>


```csharp
public bool IsValid { get; }
```
### ProviderIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorProvider.yml" sourcestartlinenumber="1">Gets the index of the locator provider in the set of providers associated with the mapView.</p>


```csharp
public int ProviderIndex { get; }
```
### ProviderName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorProvider.yml" sourcestartlinenumber="1">Gets the locator provider name.</p>


```csharp
public string ProviderName { get; }
```
### ProviderPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorProvider.yml" sourcestartlinenumber="1">Gets the locator provider path.</p>


```csharp
public string ProviderPath { get; }
```
### UseProvider

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.LocatorProvider.yml" sourcestartlinenumber="1">Gets whether the locator provider is active.</p>


```csharp
public bool UseProvider { get; }
```


