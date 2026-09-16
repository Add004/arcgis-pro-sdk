# WMSSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.WMSSubLayer.yml" sourcestartlinenumber="1">Represents a WMS sublayer.</p>


## Object Signature

```csharp
public sealed class WMSSubLayer : Layer, IMetadataInfo, IMetadataSource
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.WMSSubLayer.yml" sourcestartlinenumber="1">Gets the layer's definition which is null for WMS sublayers.</p>


```csharp
public override CIMBaseLayer GetDefinition()
```
### GetStyleName()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.WMSSubLayer.yml" sourcestartlinenumber="1">Gets the current layer style of the WMS sublayer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetStyleName()
```
### GetStyleNames()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.WMSSubLayer.yml" sourcestartlinenumber="1">returns the Style names of the WMS sublayer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetStyleNames()
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.WMSSubLayer.yml" sourcestartlinenumber="1">Sets the display name for the layer, however this method is not supported for this layer type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override void SetName(string newName)
```
### SetStyleName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.WMSSubLayer.yml" sourcestartlinenumber="1">Sets the specified style for the WMS sublayer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStyleName(string styleName)
```
### SupportsMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.WMSSubLayer.yml" sourcestartlinenumber="1">Gets whether the WMSSubLayer supports metadata</p>


```csharp
public override bool SupportsMetadata { get; }
```


