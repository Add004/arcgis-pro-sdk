# SystemFavoritesManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.SystemFavoritesManager.yml" sourcestartlinenumber="1">Manages the system favorites collection.  Favorites are a collection of frequently used connections to folders, databases, toolboxes,
servers, custom styles and statistical data collections.</p>


## Object Signature

```csharp
public sealed class SystemFavoritesManager
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SystemFavoritesManager.yml" sourcestartlinenumber="1">Gets the SystemFavoritesManager.</p>


```csharp
public static SystemFavoritesManager Current { get; }
```
### ExportSystemFavorites(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SystemFavoritesManager.yml" sourcestartlinenumber="1">Copies the current user favorites to the specified target path. Any file already in that location is overwritten.</p>


```csharp
public void ExportSystemFavorites(string targetPath)
```
### ExportSystemFavoritesWithPrompt()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SystemFavoritesManager.yml" sourcestartlinenumber="1">Prompts the user for a file path and copies the current system favorites to that location. Any file already in that location
is overwritten.</p>


```csharp
public void ExportSystemFavoritesWithPrompt()
```
### GetSystemFavorite(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SystemFavoritesManager.yml" sourcestartlinenumber="1">Gets the item from the system favorite collection.</p>


```csharp
public Favorite GetSystemFavorite(Item item)
```
### GetSystemFavorites()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SystemFavoritesManager.yml" sourcestartlinenumber="1">Retrieves the set of favorites from the system favorite collection.</p>


```csharp
public IReadOnlyList<Favorite> GetSystemFavorites()
```
### GetSystemFavoritesCount()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SystemFavoritesManager.yml" sourcestartlinenumber="1">Gets the total number of items marked as system favorites.</p>


```csharp
public int GetSystemFavoritesCount()
```
### RefreshSystemFavorites()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SystemFavoritesManager.yml" sourcestartlinenumber="1">Refreshes the contents of the system favorites collection.</p>


```csharp
public void RefreshSystemFavorites()
```


