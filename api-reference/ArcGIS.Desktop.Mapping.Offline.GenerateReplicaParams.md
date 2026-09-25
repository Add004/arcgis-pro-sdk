# GenerateReplicaParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Offline.html">Offline</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateReplicaParams.yml" sourcestartlinenumber="1">Specifies the parameters for creating sync
replicas from all sync enabled layers in a map</p>


## Object Signature

```csharp
public class GenerateReplicaParams
```


## Members

### GenerateReplicaParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateReplicaParams.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Mapping.Offline.GenerateReplicaParams" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public GenerateReplicaParams()
```
### DestinationFolder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateReplicaParams.yml" sourcestartlinenumber="1">Gets and sets the folder into which the local replica data will be copied (optional).</p>


```csharp
public string DestinationFolder { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Offline.GenerateReplicaParams.yml" sourcestartlinenumber="1">Gets and sets the extent of the area to be included in the replica(s).</p>


```csharp
public Envelope Extent { get; set; }
```


