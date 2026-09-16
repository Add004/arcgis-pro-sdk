# ProApp

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ProApp.yml" sourcestartlinenumber="1">Encapsulates the ArcGISPro application.</p>


## Object Signature

```csharp
public sealed class ProApp : ProBasedApp
```


## Members

### ProApp()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.ProApp.yml" sourcestartlinenumber="1">Initializes a new instance of the ArcGIS.Desktop.Core.ProApp class.</p>


```csharp
public ProApp()
```
### ProApp(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.ProApp.yml" sourcestartlinenumber="1">Initializes a new instance of the ArcGIS.Desktop.Core.ProApp class and loads the specified configuration.</p>


```csharp
public ProApp(string configuration)
```
### IANATimeZoneManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ProApp.yml" sourcestartlinenumber="1">Gets the IANA time zone manager</p>


```csharp
public static IANATimeZoneManager IANATimeZoneManager { get; }
```
### ProjectFileExtension

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ProApp.yml" sourcestartlinenumber="1">Gets the project file extension</p>


```csharp
public override string ProjectFileExtension { get; }
```
### TimeZoneManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ProApp.yml" sourcestartlinenumber="1">Gets the time zone manager.</p>


```csharp
public static TimeZoneManager TimeZoneManager { get; }
```
### TitleBarControlPopup

- Kind: property


```csharp
protected override FrameworkElement TitleBarControlPopup { get; }
```


