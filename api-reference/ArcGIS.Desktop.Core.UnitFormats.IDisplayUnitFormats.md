# IDisplayUnitFormats

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.UnitFormats.html">UnitFormats</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.IDisplayUnitFormats.yml" sourcestartlinenumber="1">Provides access to, and updating of, project unit formatting</p>


## Object Signature

```csharp
public interface IDisplayUnitFormats
```


## Members

### GetDefaultProjectUnitFormat(UnitFormatType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.IDisplayUnitFormats.yml" sourcestartlinenumber="1">Gets the default unit format in the current project for the given <xref href="ArcGIS.Desktop.Core.UnitFormats.UnitFormatType" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
DisplayUnitFormat GetDefaultProjectUnitFormat(UnitFormatType defaultFormatType)
```
### GetPredefinedProjectUnitFormats(UnitFormatType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.IDisplayUnitFormats.yml" sourcestartlinenumber="1">Gets the complete list of available unit formats for the given <xref href="ArcGIS.Desktop.Core.UnitFormats.UnitFormatType" data-throw-if-not-resolved="false"></xref></p>


```csharp
IList<DisplayUnitFormat> GetPredefinedProjectUnitFormats(UnitFormatType unitFormat)
```
### GetProjectUnitFormats(UnitFormatType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.IDisplayUnitFormats.yml" sourcestartlinenumber="1">Get the current list of unit formats in the current project for the given <xref href="ArcGIS.Desktop.Core.UnitFormats.UnitFormatType" data-throw-if-not-resolved="false"></xref></p>


```csharp
IList<DisplayUnitFormat> GetProjectUnitFormats(UnitFormatType unitFormat)
```
### SetDefaultProjectUnitFormat(DisplayUnitFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.IDisplayUnitFormats.yml" sourcestartlinenumber="1">Set the given project default unit format in the current project.</p>


```csharp
void SetDefaultProjectUnitFormat(DisplayUnitFormat defaultFormat)
```
### SetProjectUnitFormats(IList&lt;DisplayUnitFormat&gt;, DisplayUnitFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.IDisplayUnitFormats.yml" sourcestartlinenumber="1">Sets the list of project unit formats for the current project for the given <xref href="ArcGIS.Desktop.Core.UnitFormats.UnitFormatType" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
void SetProjectUnitFormats(IList<DisplayUnitFormat> availableUnits, DisplayUnitFormat defaultUnit = null)
```


