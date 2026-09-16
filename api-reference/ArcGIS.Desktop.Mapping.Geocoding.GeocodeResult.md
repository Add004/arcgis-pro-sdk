# GeocodeResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Geocoding.html">Geocoding</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult.yml" sourcestartlinenumber="1">Class that provides informtion about geocoded candidates returned
from <xref href="ArcGIS.Desktop.Mapping.Geocoding.LocatorManager.GeocodeAsync(System.String%2cSystem.Boolean%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class GeocodeResult
```


## Members

### DisplayLocation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult.yml" sourcestartlinenumber="1">Gets the display location of the geocode candidate.</p>


```csharp
public MapPoint DisplayLocation { get; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult.yml" sourcestartlinenumber="1">Gets the display zoom extent of the geocode candidate.</p>


```csharp
public Envelope Extent { get; }
```
### FieldValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult.yml" sourcestartlinenumber="1">Gets a dictionary of field names and values</p>


```csharp
public IReadOnlyDictionary<string, string> FieldValues { get; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult.yml" sourcestartlinenumber="1">Gets the formatted address label for the geocode candidate.</p>


```csharp
public string Label { get; }
```
### ProviderName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult.yml" sourcestartlinenumber="1">Gets the name of the locator provider that produced this geocode candidate.</p>


```csharp
public string ProviderName { get; }
```
### Score

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult.yml" sourcestartlinenumber="1">Gets the match score of the geocode candidate.</p>


```csharp
public double Score { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Geocoding.GeocodeResult.yml" sourcestartlinenumber="1">Returns a string representation of the geocode candidate.  This string representation is 'Label; (Score)'</p>


```csharp
public override string ToString()
```


