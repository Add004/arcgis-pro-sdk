# ClassFlagOption

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlagOption.yml" sourcestartlinenumber="1">Enumeration to represent options for classification flags for a point cloud filter.</p>


## Object Signature

```csharp
public enum ClassFlagOption
```


## Members

### Exclude

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlagOption.yml" sourcestartlinenumber="1">Points with this flag will never be displayed.</p>


```csharp
Exclude = 2
```
### Ignore

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlagOption.yml" sourcestartlinenumber="1">This flag does not contribute to point filtering. Points with this flag will be displayed,<br>
but if a point that does not have this flag is represented by another flag that is set to be displayed, then points that do not have this flag can also be displayed.
This is the default.</p>


```csharp
Ignore = 0
```
### Include

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlagOption.yml" sourcestartlinenumber="1">Points with this flag will be displayed.</p>


```csharp
Include = 1
```


