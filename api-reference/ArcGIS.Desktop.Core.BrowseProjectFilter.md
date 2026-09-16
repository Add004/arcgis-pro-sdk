# BrowseProjectFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">The BrowseProjectFilter class is used to control the behavior of the open and save dialogs
by controlling what is visible and what can be browsed into</p>


## Object Signature

```csharp
public class BrowseProjectFilter
```


## Members

### BrowseProjectFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an instance of a BrowseProjectFilter with no properties set</p>


```csharp
public BrowseProjectFilter()
```
### BrowseProjectFilter(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an instance of a BrowseProjectFilter initialized with the properties of the named daml filter declaration</p>


```csharp
public BrowseProjectFilter(string namedFilter)
```
### AddCanBeFlag(FilterFlag)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds specified filter flag to the canBeFlags collection of the BrowseProjectFilter instance</p>


```csharp
public void AddCanBeFlag(BrowseProjectFilter.FilterFlag flag)
```
### AddCanBeTypeId(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds specified typeid to the canBeTypeId collection of the BrowseProjectFilter instance</p>


```csharp
public void AddCanBeTypeId(string typeid)
```
### AddDoBrowseIntoTypeId(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds specified typeid to the doBrowseIntoTypeId collection of the BrowseProjectFilter instance</p>


```csharp
public void AddDoBrowseIntoTypeId(string typeid)
```
### AddDontBrowseIntoFlag(FilterFlag)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds specified filter flag to the dontBrowseIntoFlag collection of the BrowseProjectFilter instance</p>


```csharp
public void AddDontBrowseIntoFlag(BrowseProjectFilter.FilterFlag flag)
```
### AddDontBrowseIntoTypeId(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds specified typeid to the dontBrowseIntoTypeId collection of the BrowseProjectFilter instance</p>


```csharp
public void AddDontBrowseIntoTypeId(string typeid)
```
### AddFilter(BrowseProjectFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds an instance of a BrowseProjectFilter to the Filters collection property. used to make composite filters</p>


```csharp
public void AddFilter(BrowseProjectFilter filter)
```
### AddMustBeFlag(FilterFlag)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds specified filter flag to the mustBeFlag collection of the BrowseProjectFilter instance</p>


```csharp
public void AddMustBeFlag(BrowseProjectFilter.FilterFlag flag)
```
### AddMustNotBeFlag(FilterFlag)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds specified filter flag to the mustNotBeFlag collection of the BrowseProjectFilter instance</p>


```csharp
public void AddMustNotBeFlag(BrowseProjectFilter.FilterFlag flag)
```
### AddMustNotBeTypeId(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Adds specified typeid to the mustNotBeTypeId collection of the BrowseProjectFilter instance</p>


```csharp
public void AddMustNotBeTypeId(string typeid)
```
### BlockAllFileIdentification

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets or sets whether this filter will put the browse dialog into raw BrowseFilesMode. In raw mode, no file types are identified. This
property must be used in conjunction with BrowsingFilesMode=true.</p>


```csharp
public bool BlockAllFileIdentification { get; set; }
```
### BrowsingFilesMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets or sets whether this filter will put the browse dialog into BrowseFilesMode</p>


```csharp
public bool BrowsingFilesMode { get; set; }
```
### CanBeFlagNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an enumerable of the filter flag names from the canBeFlag collection of the BrowseProjectFilter instance</p>


```csharp
public IEnumerable<string> CanBeFlagNames { get; }
```
### CanBeTypeIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an enumerable of the typeids from the canBeTypeId collection of the BrowseProjectFilter instance</p>


```csharp
public IEnumerable<string> CanBeTypeIds { get; }
```
### CanSelect(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns true if this typeid can be selected while using this browseDialogFilter instance</p>


```csharp
public bool CanSelect(string typeID)
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns a new instance of a BrowseProjectFilter with the same properties as the one being cloned</p>


```csharp
public BrowseProjectFilter Clone()
```
### DoBrowseIntoTypeIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an enumerable of the typeids from the doBrowseIntoTypeId collection of the BrowseProjectFilter instance</p>


```csharp
public IEnumerable<string> DoBrowseIntoTypeIds { get; }
```
### DontBrowseIntoFlagNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an enumerable of the filter flag names from the dontBrowseIntoFlag collection of the BrowseProjectFilter instance</p>


```csharp
public IEnumerable<string> DontBrowseIntoFlagNames { get; }
```
### DontBrowseIntoTypeIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an enumerable of the typeids from the dontBrowseIntoTypeId collection of the BrowseProjectFilter instance</p>


```csharp
public IEnumerable<string> DontBrowseIntoTypeIds { get; }
```
### Excludes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns a reference to the set of browse places to not show in the catalog tree of the browse dialog</p>


```csharp
public ISet<string> Excludes { get; }
```
### FileExtension

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets or sets the FileExtension property of the Browse</p>


```csharp
public string FileExtension { get; set; }
```
### Filters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns the list of the Filters property of the BrowseProjectFilter instance</p>


```csharp
public IList<BrowseProjectFilter> Filters { get; }
```
### GetFilter(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets an instance of a BrowseProjectFilter defined by the named daml-declared filter</p>


```csharp
public static BrowseProjectFilter GetFilter(string filterName)
```
### GetFlagsForTypeId(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets the set of filter flags for the specified typeId.</p>


```csharp
public static IEnumerable<string> GetFlagsForTypeId(string typeid)
```
### GetNamedFilterNames()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets an enumeration of the names of all daml-declared filters</p>


```csharp
public static IEnumerable<string> GetNamedFilterNames()
```
### GetTypeIdsForFlag(FilterFlag)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets the set of typeIds for the specified filter flag.</p>


```csharp
public static IEnumerable<string> GetTypeIdsForFlag(BrowseProjectFilter.FilterFlag flag)
```
### Includes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns a reference to the set of browse places to show in the catalog tree of the browse dialog</p>


```csharp
public ISet<string> Includes { get; }
```
### InitialPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets or sets the initialPath property of the BrowseProjectFilter instance</p>


```csharp
public string InitialPath { get; set; }
```
### MustBeFlagNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an enumerable of the filter flag names from the mustBeFlag collection of the BrowseProjectFilter instance</p>


```csharp
public IEnumerable<string> MustBeFlagNames { get; }
```
### MustNotBeFlagNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an enumerable of the filter flag names from the mustNotBeFlag collection of the BrowseProjectFilter instance</p>


```csharp
public IEnumerable<string> MustNotBeFlagNames { get; }
```
### MustNotBeTypeIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Returns an enumerable of the typeids from the mustNotBeTypeId collection of the BrowseProjectFilter instance</p>


```csharp
public IEnumerable<string> MustNotBeTypeIds { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.BrowseProjectFilter.yml" sourcestartlinenumber="1">Gets or sets the name of the BrowseDialogFilter instance</p>


```csharp
public string Name { get; set; }
```


