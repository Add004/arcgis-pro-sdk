# ParcelFeatures

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelFeatures.yml" sourcestartlinenumber="1">Represents basic information about a parcel feature.</p>


## Object Signature

```csharp
public sealed class ParcelFeatures : PropertyChangedBase
```


## Members

### Lines

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelFeatures.yml" sourcestartlinenumber="1">Gets the objectIDs of the parcel line features by type.</p>


```csharp
public IReadOnlyList<KeyValuePair<string, List<long>>> Lines { get; }
```
### Points

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelFeatures.yml" sourcestartlinenumber="1">Gets the objectIDs of the point features.</p>


```csharp
public IReadOnlyList<long> Points { get; }
```


