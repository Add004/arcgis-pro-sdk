# Connectivity

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.SystemCore.html">SystemCore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.yml" sourcestartlinenumber="1">Class to provide connectivity state methods..</p>


## Object Signature

```csharp
public static class Connectivity
```


## Members

### DisableExternalTraffic

- Kind: property

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.yml" sourcestartlinenumber="1">Gets a value indicating whether web requests to ArcGIS Online resources</p>


```csharp
public static bool DisableExternalTraffic { get; }
```
### GetInternetConnectionStatus(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.yml" sourcestartlinenumber="1">Check internet connection status</p>


```csharp
public static Connectivity.ConnectionStatus GetInternetConnectionStatus(int timeout = 900)
```
### Initialize(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.yml" sourcestartlinenumber="1">Initialize</p>


```csharp
public static void Initialize(bool disableExternalTraffic)
```
### IsDisallowedDomain(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.yml" sourcestartlinenumber="1">Check if domain is disallowed for network requests</p>


```csharp
public static bool IsDisallowedDomain(string urlDomain)
```
### IsDisallowedUrl(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.yml" sourcestartlinenumber="1">Check if url is disallowed for network requests</p>


```csharp
public static bool IsDisallowedUrl(string url)
```
### IsInAirplaneMode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.yml" sourcestartlinenumber="1">Check if system is in Airplane mode</p>


```csharp
public static bool IsInAirplaneMode()
```
### IsMobileDevice()

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.yml" sourcestartlinenumber="1">Check if system is a mobile device (e.g. laptop)</p>


```csharp
public static bool IsMobileDevice()
```


