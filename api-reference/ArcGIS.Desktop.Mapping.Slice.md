# Slice

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Slice.yml" sourcestartlinenumber="1">NOTE: The base class for all Slice shapes.  It stores the properties that the Slice shapes have
in common.  You should not need to work with this class directly.</p>
<p>See <xref href="ArcGIS.Desktop.Mapping.SliceRectangle" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Mapping.SliceSphere" data-throw-if-not-resolved="false"></xref>, 
<xref href="ArcGIS.Desktop.Mapping.SliceCylinder" data-throw-if-not-resolved="false"></xref>, or <xref href="ArcGIS.Desktop.Mapping.SliceBox" data-throw-if-not-resolved="false"></xref> for
a detailed summary about each Slice type.</p>


## Object Signature

```csharp
public class Slice : ExploratoryAnalysis
```


## Members

### GetOutlineColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Slice.yml" sourcestartlinenumber="1">Get the color used to paint new geometry edges exposed by a Slice cut.  This affects all Slice objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetOutlineColorAsync()
```
### GetWireframeColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Slice.yml" sourcestartlinenumber="1">Get the color used to paint all slice wireframes shapes.  This affects all Slice objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetWireframeColorAsync()
```
### SetOutlineColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Slice.yml" sourcestartlinenumber="1">Change the color used to paint new geometry edges exposed by a Slice cut.  This affects all Slice objects in the active MapView.</p>


```csharp
public static Task SetOutlineColorAsync(CIMColor value)
```
### SetWireframeColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Slice.yml" sourcestartlinenumber="1">Change the color used to paint all slice wireframes shapes.  This affects all Slice objects in the active MapView.</p>


```csharp
public static Task SetWireframeColorAsync(CIMColor value)
```


