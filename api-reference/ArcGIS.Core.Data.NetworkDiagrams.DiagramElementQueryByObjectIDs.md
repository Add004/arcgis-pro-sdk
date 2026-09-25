# DiagramElementQueryByObjectIDs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByObjectIDs.yml" sourcestartlinenumber="1">Defines a diagram element query by specifying a set of Object IDs.</p>


## Object Signature

```csharp
public class DiagramElementQueryByObjectIDs
```


## Members

### DiagramElementQueryByObjectIDs()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByObjectIDs.yml" sourcestartlinenumber="1">Initializes a new instance of the DiagramElementQueryByObjectIDs class.</p>


```csharp
public DiagramElementQueryByObjectIDs()
```
### AddConnected

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByObjectIDs.yml" sourcestartlinenumber="1">Determines whether the connected edges and junctions of the specified elements are added to the query.</p>


```csharp
public bool AddConnected { get; set; }
```
### AddContents

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByObjectIDs.yml" sourcestartlinenumber="1">Determines whether the contents and containers of the specified elements are added to the query.</p>


```csharp
public bool AddContents { get; set; }
```
### ContainerObjectIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByObjectIDs.yml" sourcestartlinenumber="1">A list of diagram container element object IDs to add to the query.</p>


```csharp
public IReadOnlyList<long> ContainerObjectIDs { get; set; }
```
### EdgeObjectIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByObjectIDs.yml" sourcestartlinenumber="1">A list of diagram edge element object IDs to add to the query.</p>


```csharp
public IReadOnlyList<long> EdgeObjectIDs { get; set; }
```
### JunctionObjectIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByObjectIDs.yml" sourcestartlinenumber="1">A list of diagram junction element object IDs to add to the query.</p>


```csharp
public IReadOnlyList<long> JunctionObjectIDs { get; set; }
```


