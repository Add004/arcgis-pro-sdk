# IGPItemInfo

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Geoprocessing.html">Geoprocessing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">Get geoprocessing tool attributes.</p>


## Object Signature

```csharp
public interface IGPItemInfo
```


## Members

### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">Short item desctiption</p>


```csharp
string Description { get; }
```
### GetCategory()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">Toolset name</p>


```csharp
string GetCategory()
```
### GetContainerPath()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">&quot;toolbox&quot; for tool</p>


```csharp
string GetContainerPath()
```
### GetPath()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">returns path for ExecuteTool and OpenToolDialog
<br>&quot;toolbox\tool&quot; execute path
or
&quot;toolboxalias.tool&quot; for system and project tools</p>


```csharp
string GetPath()
```
### GetPhysicalPath()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">&quot;toolbox\toolset\tool&quot;</p>


```csharp
string GetPhysicalPath()
```
### IsContainer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">true when ItemType is &quot;toolbox&quot; or &quot;toolset&quot;</p>


```csharp
bool IsContainer { get; }
```
### IsExecutable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">return true when item is valid and not container</p>


```csharp
bool IsExecutable { get; }
```
### IsPortal

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">Gets if the item info is a portal item info</p>


```csharp
bool IsPortal { get; }
```
### IsSystem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">true if system tool</p>


```csharp
bool IsSystem { get; }
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">Gets if the item is valid</p>


```csharp
bool IsValid { get; }
```
### ItemID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">returns: tool - {toolbox_alias}.{ItemName}, toolbox - {toolbox_alias}, toolset - {}</p>


```csharp
string ItemID { get; }
```
### ItemName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">Tool/Toolset/Toolbox name</p>


```csharp
string ItemName { get; }
```
### ItemType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">return [&quot;function&quot;, &quot;model&quot;, &quot;script&quot;, &quot;pythonscript&quot;, &quot;custom&quot;, &quot;server&quot;, &quot;toolbox&quot;, &quot;toolset&quot;]</p>


```csharp
string ItemType { get; }
```
### Limits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">returns null or a comma separated string of prohibited actions</p>


```csharp
string Limits { get; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPItemInfo.yml" sourcestartlinenumber="1">Display name</p>


```csharp
string Title { get; }
```


