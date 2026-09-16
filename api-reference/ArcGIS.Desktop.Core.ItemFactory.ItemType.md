# ItemFactory.ItemType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.ItemType.yml" sourcestartlinenumber="1">Specifies the type of item that will be created using <xref href="ArcGIS.Desktop.Core.ItemFactory.Create(System.String%2cArcGIS.Desktop.Core.ItemFactory.ItemType)" data-throw-if-not-resolved="false"></xref>,
then added or imported to the project</p>


## Object Signature

```csharp
public enum ItemFactory.ItemType
```


## Members

### CloudItem

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.ItemType.yml" sourcestartlinenumber="1">An item will be created to reference an item available on a cloud hosted service. For example, when
the provided URL identifies a BIM or CAD file on Autodesk BIM 360 Docs, it can be downloaded and added to a map
or scene in your project.</p>


```csharp
CloudItem = 3
```
### PathItem

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.ItemType.yml" sourcestartlinenumber="1">A project item will be created and added to the current project in a manner that is appropriate for the
identified resource. For example, a map file identified by a file path will be imported and a new
MapProjectItem will be added to the project. If the path identifies a locator, a new locator connection
will be added to the project.</p>


```csharp
PathItem = 0
```
### PortalFolderItem

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.ItemType.yml" sourcestartlinenumber="1">An item will be created to reference a folder of resources that is available from the active portal.
For example, when the provided URL identifies a folder in My Content, you can use browse the returned
item's content and identify the web map you want to add to your project.</p>


```csharp
PortalFolderItem = 2
```
### PortalItem

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.ItemType.yml" sourcestartlinenumber="1">A portal item will be created to reference an item available from the active portal. For example, when
the provided URL identifies a feature layer or scene layer, you can add that portal item to a map or
scene in your project. If the URL identifies a map package, it can be downloaded and added to the
project.</p>


```csharp
PortalItem = 1
```


