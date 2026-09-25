# StreamServiceTableDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamServiceTableDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a <xref href="ArcGIS.Core.Data.Realtime.StreamServiceTableDefinition" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class StreamServiceTableDefinition : RealtimeTableDefinition, IDisposable
```


## Members

### GetArchiveFeatureServiceLayerURL()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamServiceTableDefinition.yml" sourcestartlinenumber="1">Gets the URL of a feature service layer associated to the source stream service.</p>


```csharp
public Uri GetArchiveFeatureServiceLayerURL()
```
### GetArchiveMaximumFeatureAge()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamServiceTableDefinition.yml" sourcestartlinenumber="1">Gets the maximum age for features that are archived in an associated feature service layer accessible by <xref href="ArcGIS.Core.Data.Realtime.StreamServiceFeatureClassDefinition.GetArchiveFeatureServiceLayerURL" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TimeSpan GetArchiveMaximumFeatureAge()
```
### GetArchiveUpdateInterval()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamServiceTableDefinition.yml" sourcestartlinenumber="1">Gets the update time interval of the archive feature service.</p>


```csharp
public TimeSpan GetArchiveUpdateInterval()
```
### GetRelatedFeatureServiceLayerURL()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamServiceTableDefinition.yml" sourcestartlinenumber="1">Gets the URL of a feature service layer that related attribues for streamed features.</p>


```csharp
public Uri GetRelatedFeatureServiceLayerURL()
```
### GetRelatedJoinField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamServiceTableDefinition.yml" sourcestartlinenumber="1">Gets the name of a common field that is used to relate streamed features/rows with features/rows from a feature service
accessible via <xref href="ArcGIS.Core.Data.Realtime.StreamServiceFeatureClassDefinition.GetRelatedFeatureServiceLayerURL" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string GetRelatedJoinField()
```


