# ExifData

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ExifData.yml" sourcestartlinenumber="1">ExifData captures supported Exchangeable Image File (EXIF) data.</p>


## Object Signature

```csharp
public sealed class ExifData
```


## Members

### ExifData()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.ExifData.yml" sourcestartlinenumber="1">ExifData captures supported Exchangeable Image File (EXIF) data.</p>


```csharp
public ExifData()
```
### IFD0

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ExifData.yml" sourcestartlinenumber="1">EXIF information for the attachment, from the 0th IFD.</p>


```csharp
public ExifData.ExifIFD0 IFD0 { get; set; }
```
### SubIFD

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ExifData.yml" sourcestartlinenumber="1">EXIF information for the attachment, using sub-IFD tags.</p>


```csharp
public ExifData.ExifSubIFD SubIFD { get; set; }
```


