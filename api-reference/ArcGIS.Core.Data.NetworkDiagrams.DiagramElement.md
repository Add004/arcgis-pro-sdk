# DiagramElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Represents a generic diagram element.</p>


## Object Signature

```csharp
public abstract class DiagramElement
```


## Members

### AssociatedGlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Gets the associated globalID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElement" data-throw-if-not-resolved="false"></xref>. This is the global ID of the utility network row that corresponds to this element.</p>


```csharp
public Guid AssociatedGlobalID { get; }
```
### AssociatedSourceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Gets the associated source ID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElement" data-throw-if-not-resolved="false"></xref>. This is the network source ID of the utility network row that corresponds to this element.</p>


```csharp
public int AssociatedSourceID { get; }
```
### ContainerID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Gets the container ID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElement" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int ContainerID { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Gets the geometry type.</p>


```csharp
protected virtual GeometryType GeometryType { get; }
```
### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Gets the globalID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElement" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Guid GlobalID { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Gets the ID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElement" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int ID { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Gets the object ID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElement" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public long ObjectID { get; }
```
### Shape

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElement.yml" sourcestartlinenumber="1">Gets and sets the shape of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElement" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Geometry Shape { get; set; }
```


