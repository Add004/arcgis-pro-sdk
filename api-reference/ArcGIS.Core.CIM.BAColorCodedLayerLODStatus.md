# BAColorCodedLayerLODStatus

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.BAColorCodedLayerLODStatus.yml" sourcestartlinenumber="1">Specifies the status of the level of detail.</p>


## Object Signature

```csharp
public enum BAColorCodedLayerLODStatus
```


## Members

### Available

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.BAColorCodedLayerLODStatus.yml" sourcestartlinenumber="1">Level available for map display.</p>


```csharp
Available = 0
```
### NoFeatures

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.BAColorCodedLayerLODStatus.yml" sourcestartlinenumber="1">The current area of interest does not have any features to display.</p>


```csharp
NoFeatures = 2
```
### TooManyFeatures

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.BAColorCodedLayerLODStatus.yml" sourcestartlinenumber="1">There are too many features in the current area of interest to display.</p>


```csharp
TooManyFeatures = 3
```
### UnknownError

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.BAColorCodedLayerLODStatus.yml" sourcestartlinenumber="1">Level cannot not be displayed for an unknown reason.</p>


```csharp
UnknownError = 1
```


