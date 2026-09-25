# IMappableItem

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMappableItem.yml" sourcestartlinenumber="1">Implemented by items that can be added to a map.</p>


## Object Signature

```csharp
public interface IMappableItem
```


## Members

### CanAddToMap(MapType?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMappableItem.yml" sourcestartlinenumber="1">Gets whether the item can be added to a map of the specified mapType.</p>


```csharp
bool CanAddToMap(MapType? mapType)
```
### OnAddToMap(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMappableItem.yml" sourcestartlinenumber="1">Add the item to the map.</p>


```csharp
List<string> OnAddToMap(Map map)
```
### OnAddToMap(Map, ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMappableItem.yml" sourcestartlinenumber="1">Add the item to the map or groupLayer at the specified index.</p>


```csharp
List<string> OnAddToMap(Map map, ILayerContainerEdit groupLayer, int index)
```


