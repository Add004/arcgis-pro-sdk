# StyleItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Represents an item saved in a style.</p>


## Object Signature

```csharp
public class StyleItem : PropertyChangedBase
```

## Remarks

<p>Style items are saved in style files and can be one of the types defined in <xref href="ArcGIS.Desktop.Mapping.StyleItemType" data-throw-if-not-resolved="false"></xref> enumeration. </p>


## Members

### StyleItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Construct a new <xref href="ArcGIS.Desktop.Mapping.StyleItem" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StyleItem()
```
### StyleItem(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Construct a new <xref href="ArcGIS.Desktop.Mapping.StyleItem" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StyleItem(string stylePath)
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets or sets the category of style item.</p>


```csharp
public string Category { get; set; }
```
### GeneratePreview(StyleItem, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Creates a preview image for the style item.</p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="3">This method doesn't support legend patch style items, use the GeneratePreviewAsync method
instead for generating a preview for legend patch style items.</p>


```csharp
public static ImageSource GeneratePreview(StyleItem item, int patchHeight, int patchWidth)
```
### GeneratePreviewAsync(StyleItem, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Creates a preview image for the style item.</p>


```csharp
public static Task<ImageSource> GeneratePreviewAsync(StyleItem item, int patchHeight, int patchWidth)
```
### GenerateSymbolPreview(StyleItem, CIMColor, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Creates a highlighted preview image for the symbol style item. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ImageSource GenerateSymbolPreview(StyleItem styleItem, CIMColor highlightColor, int patchHeight, int patchWidth)
```
### GetObject()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets object representing the style item.</p>


```csharp
public object GetObject()
```
### ItemType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets or sets the type of style item. Style items can be one of the types defined in <xref href="ArcGIS.Desktop.Mapping.StyleItemType" data-throw-if-not-resolved="false"></xref> enumeration.</p>


```csharp
public StyleItemType ItemType { get; set; }
```
### Key

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets or sets the key of style item.</p>


```csharp
public string Key { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets or sets the name of style item.</p>


```csharp
public string Name { get; set; }
```
### PatchHeight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets or sets the height of the preview image for the style item.</p>


```csharp
public int PatchHeight { get; set; }
```
### PatchWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets or sets the width of preview image for the style item.</p>


```csharp
public int PatchWidth { get; set; }
```
### PreviewImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets the preview image for the style item.</p>


```csharp
public ImageSource PreviewImage { get; }
```
### SetObject(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Sets the properties of the style item equal to the object passed as argument. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetObject(object itemObject)
```
### StylePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets the path to the style that this <xref href="ArcGIS.Desktop.Mapping.StyleItem" data-throw-if-not-resolved="false"></xref> came from.</p>


```csharp
public string StylePath { get; set; }
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleItem.yml" sourcestartlinenumber="1">Gets or sets the tags for style item.</p>


```csharp
public string Tags { get; set; }
```


