# GalleryItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Represents a selectable item in a <xref href="ArcGIS.Desktop.Framework.Contracts.Gallery" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class GalleryItem : IGalleryItem
```

## Remarks

<p>
    The default item template for Galleries expects GalleryItems. If you're using a custom item template you can
    fill the gallery with whatever type is appropriate.
    </p>


## Members

### GalleryItem(string, object, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Initializes a <code>GalleryItem</code> class.</p>


```csharp
public GalleryItem(string text, object icon = null, string tooltip = "", string group = "")
```
### GalleryItem(string, string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Initializes a <code>GalleryItem</code> class.</p>


```csharp
public GalleryItem(string text, string imagePath = "", string tooltip = "", string group = "")
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets the caption.</p>


```csharp
public string Caption { get; }
```
### FlipImageRTL

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets or sets a boolean indicating if the gallery item's icon should be flipped or not when the FlowDirection is Right-To-Left</p>


```csharp
public bool FlipImageRTL { get; set; }
```
### Group

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets or sets the group the gallery item belongs to.</p>


```csharp
public string Group { get; set; }
```
### Icon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets or sets the gallery item icon.</p>


```csharp
public object Icon { get; set; }
```
### IconLarge

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets or sets the large icon.</p>


```csharp
public object IconLarge { get; set; }
```
### IsGroupVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets or sets the IsGroupVisible flag.</p>


```csharp
public bool? IsGroupVisible { get; set; }
```
### Text

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets or sets the label for the gallery item.</p>


```csharp
public string Text { get; set; }
```
### Thumbnail

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets or sets the associated thumbnail.</p>


```csharp
public ImageSource Thumbnail { get; set; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets human readable name of item.  Used by Narrator.</p>


```csharp
public override string ToString()
```
### Tooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.GalleryItem.yml" sourcestartlinenumber="1">Gets or sets the tooltip to show when the mouse pauses over the gallery item.</p>


```csharp
public string Tooltip { get; set; }
```


