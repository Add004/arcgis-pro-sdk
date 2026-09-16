# ModuleSettingsWriter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ModuleSettingsWriter.yml" sourcestartlinenumber="1">Provides a mechanism for writing settings to a project.</p>


## Object Signature

```csharp
public class ModuleSettingsWriter
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ModuleSettingsWriter.yml" sourcestartlinenumber="1">When a project is saved, each loaded Module is given the opportunity to persist data.</p>


## Members

### Add(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ModuleSettingsWriter.yml" sourcestartlinenumber="1">Writes a new string value with the specified identifier to the project.</p>


```csharp
public void Add(string name, string value)
```


