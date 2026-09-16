# LayoutTrayButton

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTrayButton.yml" sourcestartlinenumber="1">Provides additional helper methods for <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref> subclasses that are added to a LayoutView Tray.</p>


## Object Signature

```csharp
public abstract class LayoutTrayButton : TrayButton
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTrayButton.yml" sourcestartlinenumber="1">In order to add a TrayButton to a LayoutView Tray, you must add your component to the &quot;esri_layouts_LayoutTrayButtons&quot; Category within DAML</p>


## Members

### LayoutTrayButton()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTrayButton.yml" sourcestartlinenumber="1">Provides additional helper methods for <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref> subclasses that are added to a LayoutView Tray.</p>


```csharp
protected LayoutTrayButton()
```
### IsVisibleOnView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTrayButton.yml" sourcestartlinenumber="1">Gets whether the tray button is visible on the view</p>


```csharp
public override bool IsVisibleOnView()
```
### Layout

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTrayButton.yml" sourcestartlinenumber="1">Gets the underlying <xref href="ArcGIS.Desktop.Layouts.Layout" data-throw-if-not-resolved="false"></xref> of the associated <xref href="ArcGIS.Desktop.Layouts.LayoutTrayButton.LayoutView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected Layout Layout { get; }
```
### LayoutView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTrayButton.yml" sourcestartlinenumber="1">Gets the associated view as a <xref href="ArcGIS.Desktop.Layouts.LayoutView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected LayoutView LayoutView { get; }
```


