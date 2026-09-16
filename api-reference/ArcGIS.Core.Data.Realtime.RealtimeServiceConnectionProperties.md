# RealtimeServiceConnectionProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeServiceConnectionProperties.yml" sourcestartlinenumber="1">Represents the properties used to connect to a real-time service such as stream service.</p>


## Object Signature

```csharp
public sealed class RealtimeServiceConnectionProperties : Connector
```


## Members

### RealtimeServiceConnectionProperties(Uri, RealtimeDatastoreType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeServiceConnectionProperties.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>RealtimeConnectionProperties</code> class.</p>


```csharp
public RealtimeServiceConnectionProperties(Uri serviceURL, RealtimeDatastoreType type)
```
### ObserverID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeServiceConnectionProperties.yml" sourcestartlinenumber="1">Gets the auto-generated Observer ID</p>


```csharp
public string ObserverID { get; }
```
### Password

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeServiceConnectionProperties.yml" sourcestartlinenumber="1">Gets and sets the password used to connect to the service.</p>


```csharp
public string Password { get; set; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeServiceConnectionProperties.yml" sourcestartlinenumber="1">Gets the RealtimeDatastoreType</p>


```csharp
public RealtimeDatastoreType Type { get; }
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeServiceConnectionProperties.yml" sourcestartlinenumber="1">Gets the service URL.</p>


```csharp
public Uri URL { get; }
```
### User

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeServiceConnectionProperties.yml" sourcestartlinenumber="1">Gets and sets the user used to connect to the service.</p>


```csharp
public string User { get; set; }
```


