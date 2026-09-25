# ItemDialog

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Represents the Browse dialog box, which provides access to project items, portal items, and items
available from a local or network disks. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class ItemDialog
```

## Remarks

<p>The Browse dialog box provides access to items that can be used in ArcGIS Pro, in the same
    manner as the Project pane. For example, a shapefile stored on a local disk is presented as a
    single item.</p>
<p>Some items may be available in the Browse dialog that are not available in the Project pane.
    Typically, these are items supported as inputs to or outputs from a geoprocessing tool, or items
    that can only be imported to a project.</p>


## Members

### ItemDialog()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Represents the Browse dialog box, which provides access to project items, portal items, and items
available from a local or network disks. This is an abstract class.</p>


```csharp
protected ItemDialog()
```
### AlwaysUseInitialLocation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Always use the InitialLocation if specified. If not specified, the initial location may be the last location opened using the current filter.</p>


```csharp
public bool AlwaysUseInitialLocation { get; set; }
```
### BrowseFilter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Gets or sets the BrowseProjectFilter used to restrict the items listed in the Browse dialog box to the subset
that is appropriate for a specific task.</p>


```csharp
public BrowseProjectFilter BrowseFilter { get; set; }
```
### Filter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Gets or sets the filter used to restrict the items listed in the Browse dialog box to the subset
that is appropriate for a specific task.</p>


```csharp
public string Filter { get; set; }
```
### InitialLocation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Gets or sets the initial location to display in the Browse dialog box.</p>


```csharp
public string InitialLocation { get; set; }
```
### PortalFolder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Gets the portal folder that is currently being browsed in the Browse dialog box.
This property is only applicable when browsing items in a portal.
the value of this property is null otherwise.</p>


```csharp
public Item PortalFolder { get; set; }
```
### PortalGroup

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Gets the portal group that is currently being browsed in the Browse dialog box.
This property is only applicable when browsing items in a portal.
the value of this property is null otherwise.</p>


```csharp
public Item PortalGroup { get; set; }
```
### ShowDialog()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Opens the Browse dialog box.</p>


```csharp
public abstract bool? ShowDialog()
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemDialog.yml" sourcestartlinenumber="1">Gets or sets the title of the Browse dialog box.</p>


```csharp
public string Title { get; set; }
```


