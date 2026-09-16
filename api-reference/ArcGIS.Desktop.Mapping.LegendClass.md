# LegendClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Represents the legend class item for a layer on a map's TOC.</p>


## Object Signature

```csharp
public class LegendClass
```


## Members

### CanEditLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets whether the label can be modified.</p>


```csharp
public bool CanEditLabel { get; }
```
### CanEditSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets whether the symbol can be modified.</p>


```csharp
public bool CanEditSymbol { get; }
```
### ClassIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets the class index.</p>


```csharp
public int ClassIndex { get; }
```
### ColorXML

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets the color represented as string in XML.</p>


```csharp
public string ColorXML { get; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets the description for the legend class.</p>


```csharp
public string Description { get; }
```
### GetColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets the color associated with this legend class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColor GetColor()
```
### GroupIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets the group index.</p>


```csharp
public int GroupIndex { get; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets the label for the legend class.</p>


```csharp
public string Label { get; }
```
### Patch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets the image patch.</p>


```csharp
public ImageSource Patch { get; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LegendClass.yml" sourcestartlinenumber="1">Gets whether legend class is visible or not.</p>


```csharp
public bool Visible { get; }
```


