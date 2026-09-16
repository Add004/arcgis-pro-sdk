# FilterDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterDefinition.yml" sourcestartlinenumber="1">Represents a building scene layer filter definition.
<remarks>
A filter definition contains up to two <xref href="ArcGIS.Desktop.Mapping.FilterBlockDefinition" data-throw-if-not-resolved="false"></xref> - one for
rendering the building as solid, one for rendering the building as a mesh (wire frame).
Once you define a filter, call <xref href="ArcGIS.Desktop.Mapping.BuildingSceneLayer.CreateFilter(ArcGIS.Desktop.Mapping.FilterDefinition)?text=CreateFilter" data-throw-if-not-resolved="false"></xref>
to apply it to the given building scene layer.  Or use <xref href="ArcGIS.Desktop.Mapping.BuildingSceneLayer.UpdateFilter(ArcGIS.Desktop.Mapping.FilterDefinition)" data-throw-if-not-resolved="false"></xref>.
</remarks></p>


## Object Signature

```csharp
public sealed class FilterDefinition
```


## Members

### FilterDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterDefinition.yml" sourcestartlinenumber="1">Creates an empty FilterDefinition.</p>


```csharp
public FilterDefinition()
```
### FilterDefinition(string, string, List&lt;FilterBlockDefinition&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterDefinition.yml" sourcestartlinenumber="1">Creates a FilterDefintion.</p>


```csharp
public FilterDefinition(string name, string description, List<FilterBlockDefinition> filterBlockDefinitions)
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterDefinition.yml" sourcestartlinenumber="1">Gets or sets the filter description.</p>


```csharp
public string Description { get; set; }
```
### FilterBlockDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterDefinition.yml" sourcestartlinenumber="1">Gets or sets a list of FilterBlockDefinitions.</p>


```csharp
public List<FilterBlockDefinition> FilterBlockDefinitions { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterDefinition.yml" sourcestartlinenumber="1">Gets the filter ID.</p>


```csharp
public string ID { get; }
```
### IsValid()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterDefinition.yml" sourcestartlinenumber="1">Determines if the filter definition is valid.</p>


```csharp
public bool IsValid()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterDefinition.yml" sourcestartlinenumber="1">Gets or sets the filter name.</p>


```csharp
public string Name { get; set; }
```


