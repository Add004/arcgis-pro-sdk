# CreateProjectSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.CreateProjectSettings.yml" sourcestartlinenumber="1">Provides the settings used to create a new project</p>


## Object Signature

```csharp
public class CreateProjectSettings
```


## Members

### CreateProjectSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CreateProjectSettings.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Core.CreateProjectSettings" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public CreateProjectSettings()
```
### CreateNewProjectFolder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CreateProjectSettings.yml" sourcestartlinenumber="1">Gets and sets a value indicating if a new folder will be created for this project</p>


```csharp
public bool CreateNewProjectFolder { get; set; }
```
### LocationPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CreateProjectSettings.yml" sourcestartlinenumber="1">Gets and sets the location where the project will be stored</p>


```csharp
public string LocationPath { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CreateProjectSettings.yml" sourcestartlinenumber="1">Gets and sets the name of the project that will be created</p>


```csharp
public virtual string Name { get; set; }
```
### TemplatePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CreateProjectSettings.yml" sourcestartlinenumber="1">Gets and sets the path to the project template that will be used to create the new project</p>


```csharp
public string TemplatePath { get; set; }
```
### TemplateType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CreateProjectSettings.yml" sourcestartlinenumber="1">Gets and sets the project template type that will be used to create the new project</p>


```csharp
public TemplateType TemplateType { get; set; }
```


