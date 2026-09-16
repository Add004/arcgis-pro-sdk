# ClipboardItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">ClipboardItem is a light-weight item representation used by Pro for copy/paste</p>


## Object Signature

```csharp
public class ClipboardItem : IFrameworkClipBoardItem, INotifyPropertyChanged
```


## Members

### ClipboardItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">ClipboardItem is a light-weight item representation used by Pro for copy/paste</p>


```csharp
public ClipboardItem()
```
### CatalogPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">Gets the catalog path</p>


```csharp
public string CatalogPath { get; }
```
### Data

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">Gets and sets any additional item data</p>


```csharp
public string Data { get; set; }
```
### DragToolTip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">Gets and sets the drag tooltip</p>


```csharp
public DragDropTooltip DragToolTip { get; set; }
```
### HashCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">Gets the HashCode for the data on clipboard</p>


```csharp
public int HashCode { get; set; }
```
### ItemInfoValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">Gets and sets the item ItemInfoValue. A lightweight representation of an item</p>


```csharp
public ItemInfoValue ItemInfoValue { get; set; }
```
### Operation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">Gets the operation mode</p>


```csharp
public OperationMode Operation { get; set; }
```
### ProcessID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">Gets the ID of the process which is associated with the Copy, Cut, or Move operation.</p>


```csharp
public int ProcessID { get; set; }
```
### PropertyChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Core.ClipboardItem.yml" sourcestartlinenumber="1">Event raised whenever a property is changed</p>


```csharp
public event PropertyChangedEventHandler PropertyChanged
```


