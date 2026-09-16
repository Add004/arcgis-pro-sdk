# DefinitionQuery

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Represents a Definition query.</p>


## Object Signature

```csharp
public class DefinitionQuery
```


## Members

### DefinitionQuery()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Creates a new instance of the DefinitionQuery object.</p>


```csharp
public DefinitionQuery()
```
### DefinitionQuery(string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Creates a new instance of the DefinitionQuery object.</p>


```csharp
public DefinitionQuery(string name, string whereClause)
```
### CanSetFilterGeometry(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Check whether the given geometry can be used as a filter geometry</p>


```csharp
public bool CanSetFilterGeometry(Geometry filterGeometry)
```
### FromCIMDefinitionFilter(CIMDefinitionFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Convert the input CIMDefinitionFilter into a DefinitionQuery.</p>


```csharp
public static DefinitionQuery FromCIMDefinitionFilter(CIMDefinitionFilter cimFilter)
```
### GeometryUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Gets the geometry uri to filter rows in the dataset.</p>


```csharp
public string GeometryUri { get; }
```
### GetFilterGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Gets the filter geometry for the definition query. This method
must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry GetFilterGeometry()
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Gets whether the definition query is valid.</p>


```csharp
public bool IsValid { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Gets or sets the name of the definition query item.</p>


```csharp
public string Name { get; set; }
```
### SetFilterGeometry(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Set the definition query filter geometry. This method
must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetFilterGeometry(Geometry filterGeometry)
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Gets the spatial reference for the geometry filter</p>


```csharp
public SpatialReference SpatialReference { get; }
```
### ToCIMDefinitionFilter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Convert the definition filter instance to a CIMDefinitionFilter</p>


```csharp
public CIMDefinitionFilter ToCIMDefinitionFilter()
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DefinitionQuery.yml" sourcestartlinenumber="1">Gets or sets the definition expression to filter rows in the dataset.</p>


```csharp
public string WhereClause { get; set; }
```


