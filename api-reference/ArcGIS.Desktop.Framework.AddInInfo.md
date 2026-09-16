# AddInInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Add-in metadata.</p>


## Object Signature

```csharp
public class AddInInfo : PropertyChangedBase, INotifyPropertyChanged
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Use <xref href="ArcGIS.Desktop.Framework.FrameworkApplication.GetAddInInfos" data-throw-if-not-resolved="false"></xref> to retrieve the collection of currently loaded add-ins.</p>


## Members

### Author

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the add-in author.</p>


```csharp
public string Author { get; set; }
```
### Company

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the company publishing the add-in.</p>


```csharp
public string Company { get; set; }
```
### ContextID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets an identifier used to specify the assembly load content the add-in should use.</p>


```csharp
public string ContextID { get; set; }
```
### Date

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the add-in's publishing date.</p>


```csharp
public string Date { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the add-in's description.</p>


```csharp
public string Description { get; set; }
```
### DigitalSignature

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the digital signature status (none, authenticated, invalid, or untrusted).</p>


```csharp
public string DigitalSignature { get; set; }
```
### ErrorMsg

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets error messages reported during processing of the add-in.</p>


```csharp
public string ErrorMsg { get; set; }
```
### FullPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the full path to the add-in.</p>


```csharp
public string FullPath { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the add-in's ID.</p>


```csharp
public string ID { get; set; }
```
### Image

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the add-in's image.</p>


```csharp
public ImageSource Image { get; set; }
```
### ImagePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the path to the add-ins specified image.</p>


```csharp
public string ImagePath { get; set; }
```
### IsCompatible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets whether or not the add-in is compatible with the running version of ArcGIS Pro.</p>


```csharp
public bool IsCompatible { get; set; }
```
### IsDeleted

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets whether or not the add-in has been deleted during the current ArcGIS Pro session.</p>


```csharp
public bool IsDeleted { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the add-in's name.</p>


```csharp
public string Name { get; set; }
```
### TargetVersion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the version of ArcGIS Pro the add-in targets.</p>


```csharp
public string TargetVersion { get; set; }
```
### Version

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.AddInInfo.yml" sourcestartlinenumber="1">Gets and sets the add-in's version number.</p>


```csharp
public string Version { get; set; }
```


