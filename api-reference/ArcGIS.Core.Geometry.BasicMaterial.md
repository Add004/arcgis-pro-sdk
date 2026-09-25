# BasicMaterial

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.Material" data-throw-if-not-resolved="false"></xref> class describing basic graphic properties.</p>


## Object Signature

```csharp
public class BasicMaterial : Material
```


## Members

### BasicMaterial()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Constructs new instance of a <xref href="ArcGIS.Core.Geometry.BasicMaterial" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public BasicMaterial()
```
### BasicMaterial(BasicMaterial)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Creates a deep copy of the <xref href="ArcGIS.Core.Geometry.BasicMaterial" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public BasicMaterial(BasicMaterial other)
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Gets or sets the color of this material.</p>


```csharp
public Color Color { get; set; }
```
### EdgeColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Gets or sets the edge color of this material.</p>


```csharp
public Color EdgeColor { get; set; }
```
### EdgeWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Gets or sets the edge width of this material.</p>


```csharp
public byte EdgeWidth { get; set; }
```
### IsCullBackFace

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Gets or sets a value representing if back-face culling is a property of this material.</p>


```csharp
public bool IsCullBackFace { get; set; }
```
### IsEqual(Material)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Determines if this material is equal to the other material.</p>


```csharp
public override bool IsEqual(Material other)
```
### Shininess

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Gets or sets the shininess of this material.</p>


```csharp
public byte Shininess { get; set; }
```
### TextureResource

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.BasicMaterial.TextureResource" data-throw-if-not-resolved="false"></xref> that contains <xref href="ArcGIS.Core.Geometry.Texture" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TextureResource TextureResource { get; set; }
```
### TransparencyPercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">Gets or sets the transparency of this material. The transparency is a value between 0 and 100 inclusive.</p>


```csharp
public byte TransparencyPercent { get; set; }
```


