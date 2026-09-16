# SliceAffectedLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p>SliceAffectedLayer objects can be used to set a layer to be 
    included or excluded from slicing.</p>
<p>Use <xref href="ArcGIS.Desktop.Mapping.SliceAffectedLayer.GetAllSliceLayersAsync" data-throw-if-not-resolved="false"></xref> to retrieve SliceAffectedLayer objects to work with.</p>


## Object Signature

```csharp
public class SliceAffectedLayer
```


## Members

### GetAllSliceLayersAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceAffectedLayer.yml" sourcestartlinenumber="1">Returns a list of SliceAffectedLayer objects for the active scene view.</p>


```csharp
public static Task<List<SliceAffectedLayer>> GetAllSliceLayersAsync()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceAffectedLayer.yml" sourcestartlinenumber="1">Unique ID for the layer.</p>


```csharp
public string ID { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceAffectedLayer.yml" sourcestartlinenumber="1">The name of the layer.</p>


```csharp
public string Name { get; }
```
### SetExcluded(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceAffectedLayer.yml" sourcestartlinenumber="1">Set whether the layer should be included or excluded in slicing.</p>


```csharp
public void SetExcluded(bool exclude)
```


