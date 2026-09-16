# IGalleryItem

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IGalleryItem.yml" sourcestartlinenumber="1">Implement this interface for a gallery item class if the gallery needs to be displayed<br>
in the gallery customization dialog.</p>


## Object Signature

```csharp
public interface IGalleryItem
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IGalleryItem.yml" sourcestartlinenumber="1">Gets the gallery item's caption in the gallery customization dialog.</p>


```csharp
string Caption { get; }
```
### FlipImageRTL

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IGalleryItem.yml" sourcestartlinenumber="1">Gets or sets a boolean indicating if the gallery item's icon should be flipped or not when the FlowDirection is Right-To-Left</p>


```csharp
bool FlipImageRTL { get; set; }
```
### Group

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IGalleryItem.yml" sourcestartlinenumber="1">Gets or sets the gallery item's group name.</p>


```csharp
string Group { get; set; }
```
### IsGroupVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IGalleryItem.yml" sourcestartlinenumber="1">Gets or sets a boolean indicating if the gallery item's belonging group is visible or not.</p>


```csharp
bool? IsGroupVisible { get; set; }
```
### Thumbnail

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IGalleryItem.yml" sourcestartlinenumber="1">Gets or sets the gallery item's icon in the gallery customization dialog.</p>


```csharp
ImageSource Thumbnail { get; set; }
```


