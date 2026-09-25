# MapTrayButton

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">Provides additional helper methods for <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref> subclasses that are added to a MapView Tray.</p>


## Object Signature

```csharp
public abstract class MapTrayButton : TrayButton, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">In order to add a TrayButton to a MapView Tray, you must add your component to the &quot;esri_mapping_MapTrayButtons&quot; Category within DAML</p>


## Members

### MapTrayButton()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">Provides additional helper methods for <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref> subclasses that are added to a MapView Tray.</p>


```csharp
protected MapTrayButton()
```
### Is2DMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">Gets whether or not the associated <xref href="ArcGIS.Desktop.Mapping.MapTrayButton.MapView" data-throw-if-not-resolved="false"></xref> is a view of a 2D Map.</p>


```csharp
protected bool Is2DMap { get; }
```
### IsLinkChart

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">Gets whether or not the associated <xref href="ArcGIS.Desktop.Mapping.MapTrayButton.MapView" data-throw-if-not-resolved="false"></xref> is a view of a KnowledgeGraph Link Chart.</p>


```csharp
protected bool IsLinkChart { get; }
```
### IsSceneLocalMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">Gets whether or not the associated <xref href="ArcGIS.Desktop.Mapping.MapTrayButton.MapView" data-throw-if-not-resolved="false"></xref> is a view of a 3D Local Scene.</p>


```csharp
protected bool IsSceneLocalMap { get; }
```
### IsVisibleOnView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">Gets whether or not this TrayButton is visible in the tray for the current <xref href="ArcGIS.Desktop.Mapping.TrayButton.Pane" data-throw-if-not-resolved="false"></xref></p>


```csharp
public override bool IsVisibleOnView()
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">Gets the underlying <xref href="ArcGIS.Desktop.Mapping.Map" data-throw-if-not-resolved="false"></xref> of the associated <xref href="ArcGIS.Desktop.Mapping.MapTrayButton.MapView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected Map Map { get; }
```
### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTrayButton.yml" sourcestartlinenumber="1">Gets the associated view as a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected MapView MapView { get; }
```


