# FavoritesManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Manages the favorites collection.  Favorites are a collection of frequently used connections to folders, databases, toolboxes,
servers, custom styles and statistical data collections.</p>


## Object Signature

```csharp
public sealed class FavoritesManager
```


## Members

### AddFavorite(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Adds an item to the favorites collection.  The item is added to the collection with the <xref href="ArcGIS.Desktop.Core.Favorite.IsAddedToAllNewProjects" data-throw-if-not-resolved="false"></xref> value
set to false.</p>


```csharp
public Favorite AddFavorite(Item item)
```
### AddFavorite(Item, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Adds an item to the favorites collection.</p>


```csharp
public Favorite AddFavorite(Item item, bool addToAllNewProjects)
```
### CanAddAsFavorite(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Gets whether the item can be added to the favorites collection.</p>


```csharp
public bool CanAddAsFavorite(Item item)
```
### ClearIsAddedToAllNewProjects(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Desktop.Core.Favorite.IsAddedToAllNewProjects" data-throw-if-not-resolved="false"></xref> value to false for the specified item in the favorite collection.</p>


```csharp
public void ClearIsAddedToAllNewProjects(Item item)
```
### Current

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Gets the FavoritesManager.</p>


```csharp
public static FavoritesManager Current { get; }
```
### ExportUserFavorites(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Copies the current user favorites to the specified target path. Any file already in that location is overwritten.</p>


```csharp
public void ExportUserFavorites(string targetPath)
```
### ExportUserFavoritesWithPrompt()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Prompts the user for a file path and copies the current user favorites to that location. Any file already in that location
is overwritten.</p>


```csharp
public void ExportUserFavoritesWithPrompt()
```
### GetFavorite(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Gets the item from the favorite collection.</p>


```csharp
public Favorite GetFavorite(Item item)
```
### GetFavorites()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Retrieves the set of favorites from the favorite collection.</p>


```csharp
public IReadOnlyList<Favorite> GetFavorites()
```
### GetFavoritesCount()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Gets the total number of items marked as favorites.</p>


```csharp
public int GetFavoritesCount()
```
### ImportUserFavorites(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Manages the favorites collection.  Favorites are a collection of frequently used connections to folders, databases, toolboxes,
servers, custom styles and statistical data collections.</p>


```csharp
public void ImportUserFavorites(string sourcePath)
```
### ImportUserFavoritesWithPrompt()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Manages the favorites collection.  Favorites are a collection of frequently used connections to folders, databases, toolboxes,
servers, custom styles and statistical data collections.</p>


```csharp
public void ImportUserFavoritesWithPrompt()
```
### InsertFavorite(Item, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Inserts an item to the favorites collection. The item is added to the collection with the <xref href="ArcGIS.Desktop.Core.Favorite.IsAddedToAllNewProjects" data-throw-if-not-resolved="false"></xref> value
set to false.</p>


```csharp
public Favorite InsertFavorite(Item item, int index)
```
### InsertFavorite(Item, int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Inserts an item to the favorites collection.</p>


```csharp
public Favorite InsertFavorite(Item item, int index, bool addToAllNewProjects)
```
### RefreshFavorites()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Refreshes the contents of the favorites collection.</p>


```csharp
public void RefreshFavorites()
```
### RemoveFavorite(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Removes an item from the favorites collection.</p>


```csharp
public void RemoveFavorite(Item item)
```
### SetIsAddedToAllNewProjects(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FavoritesManager.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Desktop.Core.Favorite.IsAddedToAllNewProjects" data-throw-if-not-resolved="false"></xref> value to true for the specified item in the favorite collection.</p>


```csharp
public void SetIsAddedToAllNewProjects(Item item)
```


