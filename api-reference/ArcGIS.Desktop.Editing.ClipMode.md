# ClipMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ClipMode.yml" sourcestartlinenumber="1">Describes options on how to clip features.</p>


## Object Signature

```csharp
public enum ClipMode
```


## Members

### Contain

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.ClipMode.yml" sourcestartlinenumber="1">Delete all features outside the clip area.</p>


```csharp
Contain = 3
```
### DiscardArea

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.ClipMode.yml" sourcestartlinenumber="1">Deletes only the features inside the clip area and keeps all other intersecting features.</p>


```csharp
DiscardArea = 1
```
### PreserveArea

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.ClipMode.yml" sourcestartlinenumber="1">Keeps only the features inside the clip area and deletes all other intersecting features.</p>


```csharp
PreserveArea = 0
```
### PreserveBothAreasSplit

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.ClipMode.yml" sourcestartlinenumber="1">Keeps all intersecting features.</p>


```csharp
PreserveBothAreasSplit = 2
```


