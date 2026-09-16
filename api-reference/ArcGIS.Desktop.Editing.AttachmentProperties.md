# AttachmentProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">Attachments may include properties to provide additional
information about the attachment.  The properties of this class
describe the properties that may be stored.</p>
<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="5">However, not all attachment tables support all properties.
Attempting to set a property where it is not currently supported
is not considered an error.  That property is silently ignored.</p>


## Object Signature

```csharp
public sealed class AttachmentProperties
```


## Members

### AttachmentProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">Default constructor for metadata - all fields are null.</p>


```csharp
public AttachmentProperties()
```
### AttachmentProperties(string, string, string, string, string, ExifData)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">Constructs attachment properties, initializing the properties with their
corresponding parameters.</p>


```csharp
public AttachmentProperties(string title, string altText, string caption, string credit, string tags, ExifData exifData)
```
### AltText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">Text that may be displayed or used in contexts where
the attachment cannot be used directly.  (For example,
a screen reader might read the alt text for an image
attachment.)</p>


```csharp
public string AltText { get; set; }
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">A caption for the attachment.</p>


```csharp
public string Caption { get; set; }
```
### Credit

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">Credit or attribution for the attachment, indicating
creator or source.</p>


```csharp
public string Credit { get; set; }
```
### ExifData

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">The EXIF data (if any) describing various attributes of the attachment.  EXIF is commonly present in
image data.</p>


```csharp
public ExifData ExifData { get; set; }
```
### Keywords

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">Keywords roughly describe the contents of the attachment.</p>


```csharp
public string Keywords { get; set; }
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">Tags roughly describe the contents of the attachment.</p>


```csharp
[Obsolete("Tags is an obsolete alias for Keywords.")]
public string Tags { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AttachmentProperties.yml" sourcestartlinenumber="1">A title for the attachment.</p>


```csharp
public string Title { get; set; }
```


