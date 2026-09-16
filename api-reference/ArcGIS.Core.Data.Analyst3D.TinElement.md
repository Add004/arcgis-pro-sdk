# TinElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">An abstract base class for objects that define TIN elements.</p>


## Object Signature

```csharp
public abstract class TinElement : CoreObjectsBase, IDisposable
```


## Members

### ElementType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets the element type of this instance.</p>


```csharp
public abstract TinElementType ElementType { get; }
```
### HasVoidZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets a value indicating if this TIN element has Z-less vertices.</p>


```csharp
public abstract bool HasVoidZ { get; }
```
### Index

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets the index number of this TIN element. The base index number for TIN elements is 1.</p>


```csharp
public int Index { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets a value indicating whether or not this TIN element is empty.</p>


```csharp
public abstract bool IsEmpty { get; }
```
### IsEqual(TinElement)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Data.Analyst3D.TinElement" data-throw-if-not-resolved="false"></xref> for equality.  Compares <xref href="ArcGIS.Core.Data.Analyst3D.TinElement.ElementType" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.Analyst3D.TinElement.Index" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsEqual(TinElement other)
```
### IsInsideDataArea

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets if this TIN element is within the interpolation zone or the data area of the TIN. See <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.GetDataArea" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public abstract bool IsInsideDataArea { get; }
```
### IsInsideExtent(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets whether this TIN element is inside the specified extent.</p>


```csharp
public abstract bool IsInsideExtent(Envelope extent)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets the length of this TIN element.  The length is in the units of the spatial reference of the TIN.
See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public virtual double Length { get; }
```
### NodeCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets the number of nodes that comprise this TIN element.</p>


```csharp
public abstract int NodeCount { get; }
```
### TagValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinElement.yml" sourcestartlinenumber="1">Gets the tag value of this TIN element.</p>


```csharp
public virtual int TagValue { get; }
```


