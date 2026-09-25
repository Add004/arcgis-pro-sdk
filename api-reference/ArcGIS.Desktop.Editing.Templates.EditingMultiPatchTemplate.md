# EditingMultiPatchTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Templates.html">Templates</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingMultiPatchTemplate.yml" sourcestartlinenumber="1">Defines how a new feature is created for a particular <xref href="ArcGIS.Desktop.Mapping.FeatureLayer?text=FeatureLayer" data-throw-if-not-resolved="false"></xref> that contains MultiPatch data.</p>


## Object Signature

```csharp
public sealed class EditingMultiPatchTemplate : EditingRowTemplate
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingMultiPatchTemplate.yml" sourcestartlinenumber="1">This implementation of <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate" data-throw-if-not-resolved="false"></xref> defines the attributes necessary to create a MultiPatch Feature within a single FeatureLayer.</p>


## Members

### IsGalleryMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingMultiPatchTemplate.yml" sourcestartlinenumber="1">Gets whether this EditingMultiPatchTemplate stores a gallery of 3D multipatch models.</p>


```csharp
public bool IsGalleryMode { get; }
```
### Multipatches

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingMultiPatchTemplate.yml" sourcestartlinenumber="1">Gets the 3D models currently stored in this Multipatch template.</p>


```csharp
public IReadOnlyCollection<Multipatch> Multipatches { get; }
```


