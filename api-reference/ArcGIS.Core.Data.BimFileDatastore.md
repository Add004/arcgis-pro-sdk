# BimFileDatastore

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatastore.yml" sourcestartlinenumber="1">Represents a BIM file datastore.</p>


## Object Signature

```csharp
public sealed class BimFileDatastore : Datastore, IDisposable
```


## Members

### BimFileDatastore(BimFileConnectionProperties)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatastore.yml" sourcestartlinenumber="1">Opens a BIM file datastore with a <xref href="ArcGIS.Core.Data.BimFileConnectionProperties" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public BimFileDatastore(BimFileConnectionProperties connectionProperties)
```
### GetConnector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatastore.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Connector" data-throw-if-not-resolved="false"></xref> associated with the currently opened BIM file data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Connector GetConnector()
```
### GetDefinition&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatastore.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the BIM file datastore.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T GetDefinition<T>(string name) where T : Definition
```
### OpenDataset&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatastore.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the BIM file.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T OpenDataset<T>(string name) where T : Dataset
```


