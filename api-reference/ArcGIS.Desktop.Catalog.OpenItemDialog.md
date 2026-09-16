# OpenItemDialog

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.OpenItemDialog.yml" sourcestartlinenumber="1">Opens the Browse dialog box and allows you to select one or more project items, portal items, or
items available from a local or network disk.</p>


## Object Signature

```csharp
public sealed class OpenItemDialog : ItemDialog
```


## Members

### OpenItemDialog()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Catalog.OpenItemDialog.yml" sourcestartlinenumber="1">Creates the Browse dialog box in a manner that allows you to get items from the project, the
active portal, or a local or network disk that will be opened or used in the current project.</p>


```csharp
public OpenItemDialog()
```
### Items

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.OpenItemDialog.yml" sourcestartlinenumber="1">Gets the items selected in the Browse dialog box.</p>


```csharp
public IList<Item> Items { get; }
```
### MultiSelect

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.OpenItemDialog.yml" sourcestartlinenumber="1">Gets and sets if the Browse dialog box will support selecting many items.</p>


```csharp
public bool MultiSelect { get; set; }
```
### ShowDialog()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.OpenItemDialog.yml" sourcestartlinenumber="1">Displays the Browse dialog box to open or use selcted items.</p>


```csharp
public override bool? ShowDialog()
```


