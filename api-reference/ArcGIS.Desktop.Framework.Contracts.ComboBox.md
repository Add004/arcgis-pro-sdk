# ComboBox

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Represents a selection control with a drop-down list that can be shown or hidden by clicking the arrow on the control. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class ComboBox : PlugIn, INotifyPropertyChanged
```

## Remarks

<p>
  All ribbon control elements share several attributes. The loadOnClick attribute determines when the control should be
  created by the framework. By default, controls appear enabled, but are not actually instantiated until they are
  clicked. This simple just-in-time (JIT) strategy improves resource utilization and startup time by deferring the instantiation
  of controls until they are initiated by the end user. Note that non-visible controls are never loaded until
  they become visible (or are executed programmatically), regardless of the value assigned to loadOnClick.
</p>
<p>
  Tooltips are defined using the tooltip sub-element and may span as many lines as necessary.  The image attribute is used
  to supply an image that will appear next to the tip text. Command tooltips also support a disabledText element, this string
  is additional displayed when the command is disabled.
</p>
<p>
  Most controls support multiple sizes in the ribbon. For example, a button can render small (small icon only),
  medium (small icon with text), and large (large icon over text). Use the smallImage and largeImage attributes to
  specify unique images for the different sizes.  Images don’t have to be graphics, you can also use XAML. You can
  also use overlayLargeImage and overlaySmallImage to draw a graphic or XAML overtop of the corresponding images. If
  the image should flip when running right-to-left, e.g. arrow buttons, set the flipImageRTL attribute to true.
</p>
<p>
  The disableIfBusy element is used to signal that the control should be disabled whenever the primary worker thread is
  busy. This prevents work from queuing up. This element is true by default. Controls that always need to be enabled such
  as the close application button should set this to false.
</p>
<p>
  All control declarations support a condition attribute allowing the assignment of a condition.  If the specified condition
  isn’t met, the control will be automatically disabled by the framework.  In addition, controls remain unloaded until their
  is met.  If no condition is specified, the control is assumed to be always relevant.
</p>


## Members

### Add(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Adds an item to the collection.</p>


```csharp
protected void Add(object item)
```
### Clear()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Removes all the items from the internal collection.</p>


```csharp
protected void Clear()
```
### CopyFrom(ICollection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Add items from an existing collection.</p>


```csharp
protected void CopyFrom(ICollection collection)
```
### Insert(int, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Inserts an element into the collection at the specified index.</p>


```csharp
protected void Insert(int index, object item)
```
### ItemCollection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Gets the combo box items.</p>


```csharp
public ReadOnlyObservableCollection<object> ItemCollection { get; }
```
### ItemTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Gets or sets the custom item template.</p>


```csharp
protected object ItemTemplate { get; set; }
```
### Move(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Moves the item at the specified index to a new location in the collection.</p>


```csharp
protected void Move(int oldIndex, int newIndex)
```
### OnDropDownOpened()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Invoked when the combo box's drop-down list is opened.</p>


```csharp
protected virtual void OnDropDownOpened()
```
### OnEnter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Invoked when the 'Enter' key is pressed inside the combo box's textbox.</p>


```csharp
protected virtual void OnEnter()
```
### OnLostKeyboardFocus(KeyboardFocusChangedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Invoked when the combo box loses keyboard focus.</p>


```csharp
protected virtual void OnLostKeyboardFocus(KeyboardFocusChangedEventArgs e)
```
### OnSelectionChange(ComboBoxItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Invoked when the selected item changes and it is a ComboBoxItem.</p>


```csharp
protected virtual void OnSelectionChange(ComboBoxItem item)
```
### OnSelectionChange(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Invoked when the selected item changes and the collection is filled with custom items.</p>


```csharp
protected virtual void OnSelectionChange(object item)
```
### OnTextChange(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Invoked when the text in the combo box's textbox changes.</p>


```csharp
protected virtual void OnTextChange(string text)
```
### Remove(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Removes the first occurrence of a specific object from the collection.</p>


```csharp
protected bool Remove(object item)
```
### RemoveAt(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Removes the element at the specified index of the collection.</p>


```csharp
protected void RemoveAt(int index)
```
### SelectedIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Gets or sets the zero-based index of the selected item.</p>


```csharp
public int SelectedIndex { get; set; }
```
### SelectedItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Gets or sets the selected combo box item.</p>


```csharp
public object SelectedItem { get; set; }
```
### Text

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBox.yml" sourcestartlinenumber="1">Gets or sets the text of the currently selected item.</p>


```csharp
public string Text { get; set; }
```


