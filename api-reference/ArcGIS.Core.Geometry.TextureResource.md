# TextureResource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.TextureResource.yml" sourcestartlinenumber="1">A texture resource class that wraps a <xref href="ArcGIS.Core.Geometry.TextureResource.Texture" data-throw-if-not-resolved="false"></xref> instance.</p>


## Object Signature

```csharp
public class TextureResource
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.TextureResource.yml" sourcestartlinenumber="1">Use the same TextureResource instance on instances of <xref href="ArcGIS.Core.Geometry.BasicMaterial" data-throw-if-not-resolved="false"></xref> that share the same texture.
Texture sharing is only supported inside of a single Multipatch. It is not supported between different multipatches.</p>


## Members

### TextureResource(Texture)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.TextureResource.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.TextureResource" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TextureResource(Texture texture)
```
### TextureResource(TextureResource)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.TextureResource.yml" sourcestartlinenumber="1">Creates a deep copy of the <xref href="ArcGIS.Core.Geometry.TextureResource" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TextureResource(TextureResource textureResource)
```
### IsEqual(TextureResource)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.TextureResource.yml" sourcestartlinenumber="1">Determines if this texture resource is equal to the other texture resource.</p>


```csharp
public bool IsEqual(TextureResource other)
```
### Texture

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.TextureResource.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Geometry.TextureResource.Texture" data-throw-if-not-resolved="false"></xref> by reference.</p>


```csharp
public Texture Texture { get; set; }
```


