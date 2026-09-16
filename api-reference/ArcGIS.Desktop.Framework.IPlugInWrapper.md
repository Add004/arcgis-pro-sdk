# IPlugInWrapper

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">The public interface for DAML defined controls.</p>


## Object Signature

```csharp
public interface IPlugInWrapper
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Controls defined in DAML and added to the ribbon control are not directly accessible
by other clients. Instead, 3rd parties can use <xref href="ArcGIS.Desktop.Framework.FrameworkApplication.GetCommandWrapper(System.String%2cSystem.Boolean%2cSystem.Boolean%2cSystem.Boolean%2cSystem.Boolean%2cSystem.Boolean%2cSystem.String)" data-throw-if-not-resolved="false"></xref> to
access a limited set of functionality such as updating a command's caption at run-time.</p>


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets or sets the visible name.</p>


```csharp
string Caption { get; set; }
```
### Checked

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets or sets the checked state of the plug-in if applicable.</p>


```csharp
bool Checked { get; set; }
```
### Children

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets the DAML IDs of all child controls if applicable.</p>


```csharp
string[] Children { get; }
```
### CommandType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets the type of plug-in.</p>


```csharp
CommandType CommandType { get; }
```
### DisabledTooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets or sets the tooltip when the plug-in is disabled.</p>


```csharp
string DisabledTooltip { get; set; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets a boolean value indicating if the plug-in is enabled in the user interface.</p>


```csharp
bool Enabled { get; }
```
### IsRelevant

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets a boolean value of true if the plugin is currently contextually relevant.</p>


```csharp
bool IsRelevant { get; }
```
### Keytip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets the DAML Keytip text.</p>


```csharp
string Keytip { get; }
```
### LargeImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets or sets the image the plug-in should use in the user interface when it is in its large state (32x32).</p>


```csharp
object LargeImage { get; set; }
```
### SmallImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets or sets the image the plug-in should use in the user interface when it is in its small state (16x16).</p>


```csharp
object SmallImage { get; set; }
```
### Tooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets or sets the text to appear in a pop-up window to give more information about the plug-in.</p>


```csharp
string Tooltip { get; set; }
```
### TooltipHeading

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IPlugInWrapper.yml" sourcestartlinenumber="1">Gets or sets the caption to appear above the tooltip in a pop-up window to give more information about the plug-in.</p>


```csharp
string TooltipHeading { get; set; }
```


