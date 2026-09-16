# DiagramTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate.yml" sourcestartlinenumber="1">Represents a diagram template.</p>


## Object Signature

```csharp
public sealed class DiagramTemplate : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate.yml" sourcestartlinenumber="1">A diagram template holds the configuration properties defining the content (diagram builder definition), and presentation (diagram layer definition) of a type of network diagram.<br>
DiagramTemplate objects are obtained from <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.GetDiagramTemplate(System.String)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.GetDiagramTemplates" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### DiagramManager

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate.yml" sourcestartlinenumber="1">Gets the diagram manager of this diagram template.</p>


```csharp
public DiagramManager DiagramManager { get; }
```
### GetNetworkDiagram(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> based on this diagram template with the specified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagram GetNetworkDiagram(string name)
```
### GetNetworkDiagrams()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>s based on this diagram template.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NetworkDiagram> GetNetworkDiagrams()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate.yml" sourcestartlinenumber="1">Gets the name of this diagram template.</p>


```csharp
public string Name { get; }
```


