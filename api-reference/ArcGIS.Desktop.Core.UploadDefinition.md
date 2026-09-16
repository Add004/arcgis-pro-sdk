# UploadDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Represents a class to provide parameters to the Upload method on EsriHttpClient class.</p>


## Object Signature

```csharp
public class UploadDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">UploadDefinition class allows you to define upload parameters.<br>
Once you create an instance of <xref href="ArcGIS.Desktop.Core.EsriHttpClient" data-throw-if-not-resolved="false"></xref>,
you can call its Upload method to upload an item</p>


## Members

### UploadDefinition(string, Item, string[])

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Default constructor. Provide the url of the portal, the item to be uploaded and
an array of tags.</p>


```csharp
public UploadDefinition(string portalURL, Item itemToUpload, string[] tags)
```
### CreateFolderIfNotPresent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets or sets a value that indicates if the folder should be created while uploading files</p>


```csharp
public bool CreateFolderIfNotPresent { get; set; }
```
### Credits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the Credits of the item being uploaded</p>


```csharp
public string Credits { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the Description of the item being uploaded</p>


```csharp
public string Description { get; set; }
```
### FolderID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the folder id of the portal folder into which the item will be uploaded</p>


```csharp
public string FolderID { get; set; }
```
### FolderName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the folder name of the portal folder into which the item will be uploaded</p>


```csharp
public string FolderName { get; set; }
```
### ItemToUpload

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the item to upload</p>


```csharp
public Item ItemToUpload { get; set; }
```
### PortalURL

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the URL of the portal to which the item will be uploaded</p>


```csharp
public string PortalURL { get; set; }
```
### Summary

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the Summary of the item being uploaded</p>


```csharp
public string Summary { get; set; }
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the tags to describe the item</p>


```csharp
public string[] Tags { get; set; }
```
### Thumbnail

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UploadDefinition.yml" sourcestartlinenumber="1">Gets and sets the path, on disk, for the thumbnail to be uploaded</p>


```csharp
public string Thumbnail { get; set; }
```


