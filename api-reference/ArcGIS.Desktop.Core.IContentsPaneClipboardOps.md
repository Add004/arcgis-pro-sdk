# IContentsPaneClipboardOps

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Support clipboard operations from your contents control</p>


## Object Signature

```csharp
public interface IContentsPaneClipboardOps
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">This should be implemented on your contents control view model.
Usually, the view model is your <xref href="ArcGIS.Desktop.Core.IContentsProvider" data-throw-if-not-resolved="false"></xref> which, in
turn, is usually your pane</p>


## Members

### CanCopyAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Can a copy to the clipboard be accomplished</p>


```csharp
Task<bool> CanCopyAsync()
```
### CanCutAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Can a cut to the clipboard be accomplished</p>


```csharp
Task<bool> CanCutAsync()
```
### CanDeleteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Can a delete (of the selected item(s)) be accomplished</p>


```csharp
Task<bool> CanDeleteAsync()
```
### CanDuplicateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Can a duplicate (of the selected item(s)) be accomplished</p>


```csharp
Task<bool> CanDuplicateAsync()
```
### CanPasteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Can a paste from the clipboard be accomplished</p>


```csharp
Task<bool> CanPasteAsync()
```
### CanPasteSpecialAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Can a paste special to the clipboard be accomplished</p>


```csharp
Task<bool> CanPasteSpecialAsync()
```
### CopyAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Copy contents to the clipboard</p>


```csharp
Task CopyAsync()
```
### CutAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Cut contents to the clipboard</p>


```csharp
Task CutAsync()
```
### DeleteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Delete contents</p>


```csharp
Task DeleteAsync()
```
### DuplicateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Duplicate the selected item(s)</p>


```csharp
Task DuplicateAsync()
```
### PasteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Paste contents to the clipboard</p>


```csharp
Task PasteAsync()
```
### PasteSpecialAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsPaneClipboardOps.yml" sourcestartlinenumber="1">Paste special contents to the clipboard</p>


```csharp
Task PasteSpecialAsync()
```


