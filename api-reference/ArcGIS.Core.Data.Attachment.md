# Attachment

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Represents a document associated with a row.</p>


## Object Signature

```csharp
public sealed class Attachment : CoreObjectsBase, IDisposable
```


## Members

### Attachment()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Initializes a new instance of the Attachment class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Attachment()
```
### Attachment(string, string, MemoryStream)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Initializes a new instance of the Attachment class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Attachment(string name, string contentType, MemoryStream data)
```
### GetAttachmentID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Gets the object ID of the attachment.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetAttachmentID()
```
### GetContentType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Gets the MIME type of the attached document.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetContentType()
```
### GetData()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Gets the attached document data.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MemoryStream GetData()
```
### GetGlobalID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Gets the global ID of the attachment if supported.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Guid GetGlobalID()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Gets the file name of the attached document.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### GetParentGlobalID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Gets the global ID of the parent row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Guid GetParentGlobalID()
```
### GetParentID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Gets the object ID of the parent row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetParentID()
```
### GetSize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Gets the size of the attached document in bytes and is calculated when the data is assigned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetSize()
```
### SetContentType(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Sets the MIME type of the attached document.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetContentType(string contentType)
```
### SetData(MemoryStream)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Sets the attached document data.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetData(MemoryStream data)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Attachment.yml" sourcestartlinenumber="1">Sets the file name of the attached document.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetName(string attachmentName)
```


