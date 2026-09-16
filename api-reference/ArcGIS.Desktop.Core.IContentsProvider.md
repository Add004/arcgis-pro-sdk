# IContentsProvider

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsProvider.yml" sourcestartlinenumber="1">Panes must implement this interface to show their Contents in the
Contents dock pane (eg a custom TOC)</p>


## Object Signature

```csharp
public interface IContentsProvider
```


## Members

### Contents

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsProvider.yml" sourcestartlinenumber="1">The Contents created by this provider.</p>


```csharp
Contents Contents { get; }
```
### ContentsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.IContentsProvider.yml" sourcestartlinenumber="1">Indicates whether the provider's contents are ready to show. Used internally. External providers should return true.</p>


```csharp
bool ContentsReady { get; }
```


