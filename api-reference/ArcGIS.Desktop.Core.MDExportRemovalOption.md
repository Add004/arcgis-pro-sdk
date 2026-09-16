# MDExportRemovalOption

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.MDExportRemovalOption.yml" sourcestartlinenumber="1">Enumeration of options for filtering sensitive content out of an item’s metadata. The item’s metadata content is filtered before
it is exported to a standard metadata format. The amount of content that is filtered out of the item’s metadata is determined by
the option selected.</p>


## Object Signature

```csharp
public enum MDExportRemovalOption
```


## Members

### esriExportExactCopy

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDExportRemovalOption.yml" sourcestartlinenumber="1">The content of the item’s current metadata is not filtered before it is exported to a standard metadata format. All content
is exported, including any sensitive information that may be present.</p>


```csharp
esriExportExactCopy = 0
```
### esriExportRemoveAllSensitive

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDExportRemovalOption.yml" sourcestartlinenumber="1">The content of the item’s metadata is filtered to remove local file paths, database connection information, URLs that do not begin
with http or https, and so on, if this information is present. The remaining metadata content is then exported to a standard metadata format.</p>


```csharp
esriExportRemoveAllSensitive = 2
```
### esriExportRemoveMachineNames

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDExportRemovalOption.yml" sourcestartlinenumber="1">The content of the item’s metadata is filtered to remove machine names from UNC paths, if they are present. The remaining metadata
content is then exported to a standard metadata format.</p>


```csharp
esriExportRemoveMachineNames = 1
```


