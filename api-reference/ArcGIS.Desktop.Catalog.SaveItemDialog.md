# SaveItemDialog

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.SaveItemDialog.yml" sourcestartlinenumber="1">Opens the Browse dialog box and allows you to save an item to the active portal or to a local or
network disk.</p>


## Object Signature

```csharp
public sealed class SaveItemDialog : ItemDialog
```


## Members

### SaveItemDialog()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Catalog.SaveItemDialog.yml" sourcestartlinenumber="1">Creates the Browse dialog box in a manner that allows you to get the file name that can be used to
save an item to the active portal or to a local or network disk.</p>


```csharp
public SaveItemDialog()
```
### DefaultExt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.SaveItemDialog.yml" sourcestartlinenumber="1">Gets and sets the default file extension.</p>


```csharp
public string DefaultExt { get; set; }
```
### FilePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.SaveItemDialog.yml" sourcestartlinenumber="1">Gets the name of the file that will be saved.</p>


```csharp
public string FilePath { get; }
```
### OverwritePrompt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.SaveItemDialog.yml" sourcestartlinenumber="1">Gets or sets if a prompt will appear when a file with the same name already exists.</p>


```csharp
public bool OverwritePrompt { get; set; }
```
### ShowDialog()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.SaveItemDialog.yml" sourcestartlinenumber="1">Displays the Browse dialog box to identify the location and name of an item that will be
saved to the active portal or to a local or network disk.</p>


```csharp
public override bool? ShowDialog()
```


