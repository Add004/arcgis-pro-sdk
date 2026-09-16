# LocatorControlConfigureProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControlConfigureProperties.yml" sourcestartlinenumber="1">Configures the properties used in initializing the LocatorControl.  If no configuration is required (that is you dont require a
location to be pre=populated for a search), leave the individual properties at their default values.</p>


## Object Signature

```csharp
public class LocatorControlConfigureProperties
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControlConfigureProperties.yml" sourcestartlinenumber="1">To refresh the LocatorControl, provide an updated LocatorControlConfigureProperties</p>


## Members

### LocatorControlConfigureProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControlConfigureProperties.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Mapping.Controls.LocatorControlConfigureProperties" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public LocatorControlConfigureProperties()
```
### AutoSearch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControlConfigureProperties.yml" sourcestartlinenumber="1">Gets and sets if the search is to occur automatically.  Default value is false.</p>


```csharp
public bool AutoSearch { get; set; }
```
### SearchText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControlConfigureProperties.yml" sourcestartlinenumber="1">Gets and sets the initial search text.</p>


```csharp
public string SearchText { get; set; }
```


