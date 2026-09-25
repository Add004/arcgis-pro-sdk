# AnnotationFeature

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Represents an annotation feature in an <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AnnotationFeature : Feature, IDisposable
```


## Members

### GetAnnotationClassID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Gets the annotation class ID of the feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetAnnotationClassID()
```
### GetGraphic()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref> for the feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMGraphic GetGraphic()
```
### GetGraphicOutline()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Gets the graphic outline.</p>


```csharp
public Geometry GetGraphicOutline()
```
### GetLinkedFeatureID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Gets the ID of the feature that this annotation feature is linked to.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetLinkedFeatureID()
```
### GetStatus()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Gets the status of the annotation feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AnnotationStatus GetStatus()
```
### SetAnnotationClassID(long)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Sets the annotation class ID of this annotation feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetAnnotationClassID(long annotationClassID)
```
### SetGraphic(CIMGraphic)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref> of the feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGraphic(CIMGraphic graphic)
```
### SetLinkedFeatureID(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Sets the linked feature id of this annotation feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLinkedFeatureID(object linkedFeatureID)
```
### SetStatus(AnnotationStatus)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeature.yml" sourcestartlinenumber="1">Sets the status of this annotation feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStatus(AnnotationStatus status)
```


