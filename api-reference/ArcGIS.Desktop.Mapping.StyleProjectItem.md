# StyleProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Represents a style project item.</p>


## Object Signature

```csharp
public sealed class StyleProjectItem : ProjectItem, IProjectItemEdit, IComparable<StyleProjectItem>, IProjectItemSelected, IDisposable, IProjectItemDetailsView, IProjectItemCustom, IProjectItemCustomSearch, ISupportsMultipleEditing
```


## Members

### CanUnreferenceStyle()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets a value which indicates whether a <xref href="ArcGIS.Desktop.Mapping.StyleProjectItem" data-throw-if-not-resolved="false"></xref> can be unreferenced.</p>


```csharp
public bool CanUnreferenceStyle()
```
### CanUpgrade

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the value which indicates if the <xref href="ArcGIS.Desktop.Mapping.StyleProjectItem" data-throw-if-not-resolved="false"></xref> can be upgraded to the current ArcGIS Pro version.</p>


```csharp
public bool CanUpgrade { get; }
```
### DictionaryConfiguration

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the dictionary configuration as a string.</p>


```csharp
public string DictionaryConfiguration { get; }
```
### DictionaryName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the name of the dictionary style.</p>


```csharp
public string DictionaryName { get; }
```
### DictionaryRevisionNumber

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the dictionary revision number as a string.</p>


```csharp
public string DictionaryRevisionNumber { get; }
```
### DictionaryUISchema

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the UI JSON schema of the dictionary as a string.</p>


```csharp
public string DictionaryUISchema { get; }
```
### DictionaryVersion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the dictionary version as a string.</p>


```csharp
public string DictionaryVersion { get; }
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Implements the dispose method (of <xref href="System.IDisposable" data-throw-if-not-resolved="false"></xref>)</p>


```csharp
public void Dispose()
```
### GetCounts()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the StyleItemType counts that are contained within a <xref href="ArcGIS.Desktop.Mapping.StyleProjectItem" data-throw-if-not-resolved="false"></xref></p>


```csharp
public Dictionary<StyleItemType, int> GetCounts()
```
### GetRepairPath()

- Kind: method


```csharp
protected override string GetRepairPath()
```
### IconViewPreviewSize

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the default IconViewPreviewSize</p>


```csharp
public const int IconViewPreviewSize = 64
```
### IsContentLoading()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Checks if the style content is loading</p>


```csharp
public bool IsContentLoading()
```
### IsCurrent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the value which indicates if the <xref href="ArcGIS.Desktop.Mapping.StyleProjectItem" data-throw-if-not-resolved="false"></xref> is using the current ArcGIS Pro version.</p>


```csharp
public bool IsCurrent { get; }
```
### IsCustomStyle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets whether the style item is a custom style.</p>


```csharp
public bool IsCustomStyle { get; }
```
### IsDictionaryStyle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets whether the style item is a dictionary style.</p>


```csharp
public bool IsDictionaryStyle { get; }
```
### IsMobileStyle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets whether the style item is a mobile style.</p>


```csharp
public bool IsMobileStyle { get; }
```
### IsReadOnly

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleProjectItem.yml" sourcestartlinenumber="1">Gets the value which indicates if the <xref href="ArcGIS.Desktop.Mapping.StyleProjectItem" data-throw-if-not-resolved="false"></xref> is read-only.</p>


```csharp
public bool IsReadOnly { get; }
```
### OnSearchReset()

- Kind: method


```csharp
protected override void OnSearchReset()
```


