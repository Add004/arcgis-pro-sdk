# TemplateType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.TemplateType.yml" sourcestartlinenumber="1">Gets and sets the project system template type that will be used to create the new project</p>


## Object Signature

```csharp
public enum TemplateType
```

## Remarks

<p>
    Gets and sets the project system template type that will be used to create the new project
    Remarks: The selected template type will be applied when creating a new project.Supplying a 
    full path to a template overrides this setting.The supplied template will be used instead of the supplied system template setting.
    </p>


## Members

### Catalog

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.TemplateType.yml" sourcestartlinenumber="1">Create a new project with an open catalog view. For example, create a project like this to manage your data.</p>


```csharp
Catalog = 0
```
### GlobalScene

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.TemplateType.yml" sourcestartlinenumber="1">Create a new project with an open 3D global scene.</p>


```csharp
GlobalScene = 3
```
### LocalScene

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.TemplateType.yml" sourcestartlinenumber="1">Create a new project with an open 3D local scene.</p>


```csharp
LocalScene = 2
```
### Map

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.TemplateType.yml" sourcestartlinenumber="1">Create a new project with an open 2D map.</p>


```csharp
Map = 1
```
### Untitled

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.TemplateType.yml" sourcestartlinenumber="1">Start working in ArcGIS Pro without creating a project first. You can save a project later if you want to keep your work.</p>


```csharp
Untitled = 4
```


