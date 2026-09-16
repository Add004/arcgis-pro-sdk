# Row

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Represents a row in a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class Row : CoreObjectsBase, IDisposable
```


## Members

### AddAttachment(Attachment)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Adds a given attachment to a row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long AddAttachment(Attachment attachment)
```
### Delete()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Deletes the row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Delete()
```
### DeleteAttachments(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Deletes attachment(s) provided by attachmentID that are associated with the row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<long, Exception> DeleteAttachments(IEnumerable<long> attachmentIDs = null)
```
### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FindField(string fieldName)
```
### GetAttachments(IEnumerable&lt;long&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of attachments based on the requested <code class="paramref">attachmentIDs</code> for a given row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Attachment> GetAttachments(IEnumerable<long> attachmentIDs = null, bool infoOnly = false)
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> containing the fields of the row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### GetGlobalID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets the global ID in the form of <xref href="System.Guid" data-throw-if-not-resolved="false"></xref> associated with the row.  If the row does not have a global ID, an empty Guid is returned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Guid GetGlobalID()
```
### GetObjectID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets the object ID of the row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetObjectID()
```
### GetOriginalValue(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets the original value of a field at the given index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual object GetOriginalValue(int index)
```
### GetTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets the parent <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> of this row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table GetTable()
```
### HasValueChanged(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets a value indicating whether the value of the field at the given index has changed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasValueChanged(int index)
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its index position.
This indexer must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual object this[int index] { get; set; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its attribute name or alias name.
This indexer must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[string fieldName] { get; set; }
```
### Store()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Stores the row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Store()
```
### UpdateAttachment(Attachment)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Row.yml" sourcestartlinenumber="1">Updates the properties of an existing attachment fetched using GetAttachment with new values
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateAttachment(Attachment updatedAttachment)
```


