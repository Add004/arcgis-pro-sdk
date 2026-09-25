# ClassFlag

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlag.yml" sourcestartlinenumber="1">Represents a classification flag for a point cloud filter.</p>


## Object Signature

```csharp
public class ClassFlag
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlag.yml" sourcestartlinenumber="1">When a classification is carried out on lidar data, points may fall into more than one category of the classification.
Classification flags are used to provide a secondary description or classification for lidar points.</p>


## Members

### ClassFlag(int, ClassFlagOption)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlag.yml" sourcestartlinenumber="1">Creates a ClassFlag.</p>


```csharp
public ClassFlag(int classFlag, ClassFlagOption classFlagOption = ClassFlagOption.Ignore)
```
### ClassFlagOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlag.yml" sourcestartlinenumber="1">Gets or sets the ClassFlagOption</p>


```csharp
public ClassFlagOption ClassFlagOption { get; set; }
```
### Flag

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ClassFlag.yml" sourcestartlinenumber="1">Gets or sets the Flag.</p>


```csharp
public int Flag { get; set; }
```


