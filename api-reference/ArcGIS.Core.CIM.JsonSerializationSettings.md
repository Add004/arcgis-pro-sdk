# JsonSerializationSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.JsonSerializationSettings.yml" sourcestartlinenumber="1">A collection of settings that control JSON serialization.</p>


## Object Signature

```csharp
public class JsonSerializationSettings
```


## Members

### JsonSerializationSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.JsonSerializationSettings.yml" sourcestartlinenumber="1">A collection of settings that control JSON serialization.</p>


```csharp
public JsonSerializationSettings()
```
### OmitDefaults

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.JsonSerializationSettings.yml" sourcestartlinenumber="1">Gets and sets whether to omit properties that have their default values from JSON output. Default value is true.
This behavior is designed to produce smaller JSON payloads.</p>


```csharp
public bool OmitDefaults { get; set; }
```
### PrettyPrint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.JsonSerializationSettings.yml" sourcestartlinenumber="1">Gets and sets whether JSON output should be formatted with whitespace and newlines. Default value is true.</p>


```csharp
public bool PrettyPrint { get; set; }
```


