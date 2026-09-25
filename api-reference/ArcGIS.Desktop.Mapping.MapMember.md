# MapMember

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Represents the abstract base class for layers and standalone tables.</p>


## Object Signature

```csharp
public abstract class MapMember : PropertyChangedBase, IMetadataInfo, IMetadataSource
```


## Members

### CanClearTime()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets if the mapMember supports time filtering and can clear the time filter.  Clearing the time filter ensures that
data is always shown.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool CanClearTime()
```
### CanConfigurePopups

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets a value indicating whether the MapMember's pop-ups can be configured.</p>


```csharp
public bool CanConfigurePopups { get; }
```
### CanGetTime()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets if the mapMember supports time filtering.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual bool CanGetTime()
```
### CanSetTime(TimeParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets if the mapMember supports time filtering and if the specified time parameters are valid.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual bool CanSetTime(TimeParameters timeParams)
```
### ClearTime()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Clears the time filter for the mapMember. Clearing the time filter ensures that
data is always shown.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual void ClearTime()
```
### ConnectionStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets a value indicating the MapMember's connection status.</p>


```csharp
public ConnectionStatus ConnectionStatus { get; }
```
### ExportPopupConfiguration(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Exports the MapMember's current popup configuration to a .pop file.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportPopupConfiguration(string filePath)
```
### GetCanEditMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets whether the MapMember metadata can be edited or not. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public virtual bool GetCanEditMetadata()
```
### GetDataConnection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets a CIMDataConnection value object.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual CIMDataConnection GetDataConnection()
```
### GetDataTimeExtent(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets the time extent of the data for the specified fieldName - that is the minimum and maximum dates present in the data.<br>
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public TimeExtent GetDataTimeExtent(string fieldName)
```
### GetDataTimeIntervals(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets the set of time intervals for the specified field name present in the data.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetDataTimeIntervals(string fieldName)
```
### GetMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets the MapMember metadata. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public virtual string GetMetadata()
```
### GetPath()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets the path of the dataset underneath the MapMember as a Uri.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Uri GetPath()
```
### GetTime()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets the current time parameters for the mapMember.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public TimeParameters GetTime()
```
### GetUseSourceMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets whether or not the MapMember stores its own metadata or uses metadata
retrieved from its source. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public virtual bool GetUseSourceMetadata()
```
### ImportPopupConfiguration(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Imports a .pop file and sets the popup configuration for the MapMember.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ImportPopupConfiguration(string filePath)
```
### IsTimeSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets if time is supported for this mapMember. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool IsTimeSupported()
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Get the map which the MapMember belongs to.</p>


```csharp
public Map Map { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets the display name of the MapMember.</p>


```csharp
public string Name { get; }
```
### SetDataConnection(CIMDataConnection, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Updates a MapMember's data source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDataConnection(CIMDataConnection dataConnection, bool validateConnection = true)
```
### SetMetadata(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Sets the MapMember metadata. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public virtual void SetMetadata(string metadataXml)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Sets the display name for the MapMember.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual void SetName(string newName)
```
### SetShowPopups(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Toggles enabling pop-ups for the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShowPopups(bool showPopups)
```
### SetTime(TimeParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Sets the specified time parameters for the mapMember.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetTime(TimeParameters timeParams)
```
### SetUseSourceMetadata(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Sets whether or not the MapMember will use its own metadata or the metadata
from its underyling source (if it has one). This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual void SetUseSourceMetadata(bool useSource)
```
### ShowPopups

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets a value indicating whether the MapMember is configured to show pop-ups when a feature is clicked.</p>


```csharp
public bool ShowPopups { get; }
```
### SupportsMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets whether the MapMember supports metadata</p>


```csharp
public virtual bool SupportsMetadata { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Returns the display name of the MapMember.</p>


```csharp
public override string ToString()
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMember.yml" sourcestartlinenumber="1">Gets the unique path of this MapMember.</p>


```csharp
public string URI { get; }
```


