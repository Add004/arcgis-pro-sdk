# SymbolSearcherSearchFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchFilter.yml" sourcestartlinenumber="1">Use SymbolSearcherSearchFilter to filter the symbol search of the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl" data-throw-if-not-resolved="false"></xref>.  The search can be filtered by all styles, project only styles, or by one or many <xref href="ArcGIS.Desktop.Mapping.StyleProjectItem" data-throw-if-not-resolved="false"></xref>s.</p>


## Object Signature

```csharp
public class SymbolSearcherSearchFilter
```


## Members

### SymbolSearcherSearchFilter(bool, StyleProjectItem)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchFilter.yml" sourcestartlinenumber="1">Creates a SymbolSearcherSearchFilter that can be used to set the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.SearchFilterStyle" data-throw-if-not-resolved="false"></xref> property.<br>
If no parameters are specified for the constructor the SymbolSearcherControl searches all styles.</p>


```csharp
public SymbolSearcherSearchFilter(bool createProjectStyleFilter = false, StyleProjectItem style = null)
```
### IsAllSystemStyles

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchFilter.yml" sourcestartlinenumber="1">Gets if the SearchItemType is SymbolSearcherSearchStyle.AllStyles</p>


```csharp
public bool IsAllSystemStyles { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchFilter.yml" sourcestartlinenumber="1">Gets the helper name - used in the symbol searcher</p>


```csharp
public string Name { get; }
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchFilter.yml" sourcestartlinenumber="1">Gets the helper style path name - used in the symbol searcher</p>


```csharp
public string Path { get; }
```


