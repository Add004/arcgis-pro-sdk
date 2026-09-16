# FilterBlockDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterBlockDefinition.yml" sourcestartlinenumber="1">Represents a building scene layer filter block.</p>


## Object Signature

```csharp
public sealed class FilterBlockDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterBlockDefinition.yml" sourcestartlinenumber="1">Each building scene layer <xref href="ArcGIS.Desktop.Mapping.FilterDefinition" data-throw-if-not-resolved="false"></xref> can contain up to two blocks:<br>
o One that renders the building as a solid (FilterBlockMode == Object3DRenderingMode.None)<br>
o One that renders the building as a wireframe (FilterBlockMode == Object3DRenderingMode.Wireframe)<br></p>


## Members

### FilterBlockDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterBlockDefinition.yml" sourcestartlinenumber="1">Creates an empty FilterBlockDefinition.</p>


```csharp
public FilterBlockDefinition()
```
### FilterBlockDefinition(string, Object3DRenderingMode, Dictionary&lt;string, List&lt;string&gt;&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterBlockDefinition.yml" sourcestartlinenumber="1">Creates a FilterBlockDefinition.</p>


```csharp
public FilterBlockDefinition(string title, Object3DRenderingMode filterBlockMode, Dictionary<string, List<string>> selectedValues)
```
### FilterBlockMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterBlockDefinition.yml" sourcestartlinenumber="1">Gets or sets the FilterBlockMode.</p>


```csharp
public Object3DRenderingMode FilterBlockMode { get; set; }
```
### SelectedValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterBlockDefinition.yml" sourcestartlinenumber="1">Gets or sets the selected values for a FilterBlock.</p>


```csharp
public Dictionary<string, List<string>> SelectedValues { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FilterBlockDefinition.yml" sourcestartlinenumber="1">Gets or sets the FilterBlock title.</p>


```csharp
public string Title { get; set; }
```


