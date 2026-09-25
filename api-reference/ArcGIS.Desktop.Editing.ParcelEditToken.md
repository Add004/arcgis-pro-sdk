# ParcelEditToken

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEditToken.yml" sourcestartlinenumber="1">A ParcelEditToken represents a collection of parcel feature edits; the edits will occur after the edit operation has completed.</p>


## Object Signature

```csharp
public sealed class ParcelEditToken
```


## Members

### CreatedFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEditToken.yml" sourcestartlinenumber="1">Gets the objectIds of the parcel features created.</p>


```csharp
public SelectionSet CreatedFeatures { get; }
```
### ModifiedFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEditToken.yml" sourcestartlinenumber="1">Gets the objectIds of the parcel features modified.</p>


```csharp
public SelectionSet ModifiedFeatures { get; }
```


