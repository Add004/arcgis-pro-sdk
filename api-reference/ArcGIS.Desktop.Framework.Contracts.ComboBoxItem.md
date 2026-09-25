# ComboBoxItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Represents a selectable item in a <xref href="ArcGIS.Desktop.Framework.Contracts.ComboBox" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class ComboBoxItem
```

## Remarks

<p>
    The default item template for ComboBox expects ComboBoxItems. If you're using a custom item template you can
    fill the combo box with whatever type is appropriate.
    </p>


## Members

### ComboBoxItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Initializes a <code>ComboBoxItem</code> class.</p>


```csharp
public ComboBoxItem()
```
### ComboBoxItem(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Initializes a <code>ComboBoxItem</code> class.</p>


```csharp
public ComboBoxItem(string text)
```
### ComboBoxItem(string, object)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Initializes a ComboBoxItem class.</p>


```csharp
public ComboBoxItem(string text, object icon)
```
### ComboBoxItem(string, object, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Initializes a <code>ComboBoxItem</code> class.</p>


```csharp
public ComboBoxItem(string text, object icon = null, string tooltip = "")
```
### ComboBoxItem(string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Initializes a <code>ComboBoxItem</code> class.</p>


```csharp
public ComboBoxItem(string text, string imagePath = "", string tooltip = "")
```
### Group

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Gets or sets the Group for the combo box item.</p>


```csharp
public string Group { get; set; }
```
### Icon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Gets or sets the icon for the combo box item.</p>


```csharp
public object Icon { get; set; }
```
### Text

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Gets or sets the label for the combo box item.</p>


```csharp
public string Text { get; set; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Overridden to return the item's Text property as its ToString representation.</p>


```csharp
public override string ToString()
```
### Tooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ComboBoxItem.yml" sourcestartlinenumber="1">Gets or sets the tooltip for the combo box item.</p>


```csharp
public string Tooltip { get; set; }
```


