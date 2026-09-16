# NamedTraceConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The NamedTraceConfiguration object defines a set of input parameters to a tracing operation.</p>


## Object Signature

```csharp
public class NamedTraceConfiguration
```


## Members

### Creator

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The creator of the named trace configuration.</p>


```csharp
public string Creator { get; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The description of the named trace configuration.</p>


```csharp
public string Description { get; }
```
### GetTraceConfiguration()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration" data-throw-if-not-resolved="false"></xref> representation of this named trace configuration.</p>


```csharp
public TraceConfiguration GetTraceConfiguration()
```
### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The GlobalID of the named trace configuration.</p>


```csharp
public Guid GlobalID { get; }
```
### MinimumStartingLocations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The minimum number of starting locations for the named trace configuration.</p>


```csharp
public MinimumStartingLocations MinimumStartingLocations { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The user-defined name for the named trace configuration.</p>


```csharp
public string Name { get; }
```
### ResultTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The types of results that can be returned from a named trace configuration.</p>


```csharp
public IReadOnlyList<ResultType> ResultTypes { get; }
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The tags of a named trace configuration.</p>


```csharp
public IReadOnlyList<string> Tags { get; }
```
### TraceType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration.yml" sourcestartlinenumber="1">The type of trace to perform.</p>


```csharp
public string TraceType { get; }
```


