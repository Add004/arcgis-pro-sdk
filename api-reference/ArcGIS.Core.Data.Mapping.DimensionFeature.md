# DimensionFeature

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Represents a dimension feature in a <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class DimensionFeature : Feature, IDisposable
```


## Members

### GetCustomLength()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Get the custom length of the dimension feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetCustomLength()
```
### GetDimensionExtensionOption()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Gets the dimension extension option for the feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DimensionPartOptions GetDimensionExtensionOption()
```
### GetDimensionLineOption()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Gets the dimension line option for the dimension feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DimensionPartOptions GetDimensionLineOption()
```
### GetDimensionMarkerOption()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Get the marker option for this feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DimensionPartOptions GetDimensionMarkerOption()
```
### GetDimensionShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Core.CIM.CIMDimensionShape" data-throw-if-not-resolved="false"></xref> for the feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMDimensionShape GetDimensionShape()
```
### GetDimensionType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Gets the dimension type for this feature
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DimensionType GetDimensionType()
```
### GetLength()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Gets the length of the dimension feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetLength()
```
### GetStyleID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Gets the style ID for the dimension feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetStyleID()
```
### GetUseCustomLength()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Gets if the dimension feature is using the custom length.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetUseCustomLength()
```
### SetCustomLength(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Sets the custom length for the dimension feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCustomLength(double length)
```
### SetDimensionExtensionOption(DimensionPartOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Sets the dimension extension for the feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDimensionExtensionOption(DimensionPartOptions option)
```
### SetDimensionLineOption(DimensionPartOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Sets the dimension line option for the dimension feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDimensionLineOption(DimensionPartOptions option)
```
### SetDimensionMarkerOption(DimensionPartOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Set the marker option for this feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDimensionMarkerOption(DimensionPartOptions option)
```
### SetDimensionShape(CIMDimensionShape)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Sets a <xref href="ArcGIS.Core.CIM.CIMDimensionShape" data-throw-if-not-resolved="false"></xref> for the feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDimensionShape(CIMDimensionShape dimensionShape)
```
### SetDimensionType(DimensionType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Sets dimension type for this feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDimensionType(DimensionType dimensionType)
```
### SetStyleID(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Sets the style ID for the dimension feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStyleID(int styleID)
```
### SetUseCustomLength(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeature.yml" sourcestartlinenumber="1">Sets if the dimension feature is using the custom length.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseCustomLength(bool useCustomLength)
```


