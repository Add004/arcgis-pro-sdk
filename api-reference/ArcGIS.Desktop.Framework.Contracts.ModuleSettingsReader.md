# ModuleSettingsReader

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ModuleSettingsReader.yml" sourcestartlinenumber="1">Provides a mechanism for reading settings written to a project.</p>


## Object Signature

```csharp
public class ModuleSettingsReader
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ModuleSettingsReader.yml" sourcestartlinenumber="1">When a project loads, each loaded Module is given a chance to read any custom settings
it may have written to the project (see <xref href="ArcGIS.Desktop.Framework.Contracts.Module.OnReadSettingsAsync(ArcGIS.Desktop.Framework.Contracts.ModuleSettingsReader)" data-throw-if-not-resolved="false"></xref>). When
a module loads for the first time and a project has already been opened, the module is also
afforded the same opportunity.</p>


## Members

### Get(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ModuleSettingsReader.yml" sourcestartlinenumber="1">Returns the object persisted in the project identified by the specified key.</p>


```csharp
public object Get(string key)
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ModuleSettingsReader.yml" sourcestartlinenumber="1">Gets or sets the object persisted in the project identified by the specified key.</p>


```csharp
public object this[string key] { get; set; }
```


