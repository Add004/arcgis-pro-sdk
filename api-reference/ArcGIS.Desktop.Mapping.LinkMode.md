# LinkMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p>Defines the method used to link multiple 2D and 3D views together.</p>
<p>This enumeration has a FlagsAttribute attribute that allows a bitwise combination of its member values.</p>


## Object Signature

```csharp
[Flags]
public enum LinkMode
```


## Members

### Center

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LinkMode.yml" sourcestartlinenumber="1">Views will look at the same location. When linking 2D and 3D views, the locations are approximated.</p>


```csharp
Center = 1
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LinkMode.yml" sourcestartlinenumber="1">Views are not linked.</p>


```csharp
None = 0
```
### Scale

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LinkMode.yml" sourcestartlinenumber="1">Views will maintain the same scale and rotation. When linking 2D and 3D views, the scales are approximated between view types.</p>


```csharp
Scale = 2
```


