# LayoutOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Gets and sets the application layout options.</p>


## Object Signature

```csharp
public class LayoutOptions
```


## Members

### DefaultGuideColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Gets the application default layout guide color.</p>


```csharp
public CIMColor DefaultGuideColor { get; }
```
### GetGuideColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Gets the application layout guide color.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColor GetGuideColor()
```
### KeepLastToolActive

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Gets and sets whether the insert tool stays active or reverts
back to select after adding a new element.</p>


```csharp
public bool KeepLastToolActive { get; set; }
```
### LayoutTemplatePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Gets and sets the default path for the location of the layout template gallery.</p>


```csharp
public string LayoutTemplatePath { get; set; }
```
### OverrideLayerVisibilityForNewMapFrames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Gets and sets whether new map frames override map layer visibility by default.</p>


```csharp
public bool OverrideLayerVisibilityForNewMapFrames { get; set; }
```
### SetGuideColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Sets the layout guide color.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGuideColor(CIMColor color)
```
### ShowXYPositionOnElement

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Gets and sets whether an xy position tooltip is displayed when moving graphic elements.</p>


```csharp
public bool ShowXYPositionOnElement { get; set; }
```
### WarnAboutAssociatedSurrounds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutOptions.yml" sourcestartlinenumber="1">Gets and sets whether a warning will be shown when deleting a map frame
will result in other elements in the layout being deleted.</p>


```csharp
public bool WarnAboutAssociatedSurrounds { get; set; }
```


