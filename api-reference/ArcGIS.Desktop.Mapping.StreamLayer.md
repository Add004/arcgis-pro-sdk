# StreamLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Represents layer with a collection of real-time features and their visual representation.</p>


## Object Signature

```csharp
public sealed class StreamLayer : FeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject, IDisposable
```

## Remarks

<p>
    Stream layer is a type of <xref href="ArcGIS.Desktop.Mapping.FeatureLayer" data-throw-if-not-resolved="false"></xref>.To create a StreamLayer, you must call CreateLayer method of the <xref href="ArcGIS.Desktop.Mapping.LayerFactory?text=LayerFactory" data-throw-if-not-resolved="false"></xref> class, instead of directly using a constructor.
    </p>
<p>
    When you use <xref href="ArcGIS.Desktop.Mapping.LayerFactory.CreateLayer%60%601(ArcGIS.Desktop.Mapping.LayerCreationParams%2cArcGIS.Desktop.Mapping.ILayerContainerEdit)" data-throw-if-not-resolved="false"></xref>, you need to pass in a <xref href="ArcGIS.Desktop.Mapping.FeatureLayerCreationParams" data-throw-if-not-resolved="false"></xref>.
    You should set <xref href="ArcGIS.Desktop.Mapping.UniqueValueRendererDefinition" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.ClassBreaksRendererDefinition" data-throw-if-not-resolved="false"></xref> in a <xref href="ArcGIS.Desktop.Mapping.FeatureLayerCreationParams" data-throw-if-not-resolved="false"></xref>
    only when the source stream service has associated archieved feature service layer. See <xref href="ArcGIS.Core.Data.Realtime.StreamServiceFeatureClassDefinition.GetArchiveFeatureServiceLayerURL" data-throw-if-not-resolved="false"></xref> for details.
    That is because at the creation time a stream layer starts with empty set of features.
    </p>
<p>
    You can call <xref href="ArcGIS.Desktop.Mapping.FeatureLayer.CreateRenderer(ArcGIS.Desktop.Mapping.RendererDefinition)" data-throw-if-not-resolved="false"></xref> anytime later once you have sufficient features to compute and assign a <xref href="ArcGIS.Core.CIM.CIMUniqueValueRenderer" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.CIM.CIMClassBreaksRenderer" data-throw-if-not-resolved="false"></xref> to a stream layer.
    </p>


## Members

### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Releases this object's unmanaged resources.</p>


```csharp
public void Dispose()
```
### Finalize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Represents layer with a collection of real-time features and their visual representation.</p>


```csharp
protected override void Finalize()
```
### GetExpirationMaxAge()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Gets the expiration maximum age for features. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TimeSpan GetExpirationMaxAge()
```
### GetExpirationMaxCount()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Gets the expiration maximum feature count. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ulong GetExpirationMaxCount()
```
### GetExpirationMethod()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Gets the current expiration method. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureExpirationMethod GetExpirationMethod()
```
### GetFeatureClass()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Returns the underlying <xref href="ArcGIS.Core.Data.Realtime.RealtimeFeatureClass?text=FeatureClass" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeFeatureClass GetFeatureClass()
```
### IsStreamingConnectionOpen

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Gets whether this <xref href="ArcGIS.Desktop.Mapping.StreamLayer" data-throw-if-not-resolved="false"></xref>'s streaming connection is open (started).</p>


```csharp
public bool IsStreamingConnectionOpen { get; }
```
### SearchAndSubscribe(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Searches the table for existing rows using the query criteria and then subscribes to receive row events.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeCursor SearchAndSubscribe(QueryFilter queryFilter, bool useRecyclingCursor)
```
### SetExpirationMaxAge(TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Sets the expiration maximum age for features. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMaxAge(TimeSpan expirationMaxAge)
```
### SetExpirationMaxCount(ulong)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Gets the expiration maximum feature count. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMaxCount(ulong expirationMaxCount)
```
### SetExpirationMethod(FeatureExpirationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Sets the expiration method to the table. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMethod(FeatureExpirationMethod featureExpirationMethod)
```
### StartStreaming()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Sets the stream layer to a state where it starts listening to broadcasts from a real-time data source.</p>


```csharp
public void StartStreaming()
```
### StopStreaming()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Stops listening to streams from a real-time data source.</p>


```csharp
public void StopStreaming()
```
### Subscribe(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StreamLayer.yml" sourcestartlinenumber="1">Subscribe to receive row events. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeCursor Subscribe(QueryFilter queryFilter, bool useRecyclingCursor)
```


