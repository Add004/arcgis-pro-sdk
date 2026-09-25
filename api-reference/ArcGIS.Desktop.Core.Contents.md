# Contents

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Contents.yml" sourcestartlinenumber="1">IContentsProviders will return an instance of this class for their &quot;contents&quot;.
Contents are shown in the Contents Dock pane when the IContentsProvider is
activated.</p>


## Object Signature

```csharp
public class Contents
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Contents.yml" sourcestartlinenumber="1">Typically:<br>
The ContentsView is your user control or &quot;UI&quot;<br>
The ContentsViewModel is the UI view model and should be your pane (it is usually also the IContentsProvider)<br>
The OperationManager is the operation manager you want to contain Undo/Redo operations when
your content is active. For example: see the code snipped below. Your pane has been activated and is being
asked to provide its Contents via <xref href="ArcGIS.Desktop.Core.IContentsProvider.Contents" data-throw-if-not-resolved="false"></xref></p>


## Members

### Contents()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Contents.yml" sourcestartlinenumber="1">IContentsProviders will return an instance of this class for their &quot;contents&quot;.
Contents are shown in the Contents Dock pane when the IContentsProvider is
activated.</p>


```csharp
public Contents()
```
### ContentsView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Contents.yml" sourcestartlinenumber="1">Gets the UI element (typically a user control) associated with your content</p>


```csharp
public FrameworkElement ContentsView { get; set; }
```
### ContentsViewModel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Contents.yml" sourcestartlinenumber="1">The associated view model to be used for IContentsControl, IContentsPaneClipboardOps and INotifyPropertyChanged</p>


```csharp
public object ContentsViewModel { get; set; }
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Contents.yml" sourcestartlinenumber="1">Gets and sets the associated operations manager with your contents</p>


```csharp
public OperationManager OperationManager { get; set; }
```


