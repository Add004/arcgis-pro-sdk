# IExtensionConfig

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IExtensionConfig.yml" sourcestartlinenumber="1">Provides access to members that describe an extension.</p>


## Object Signature

```csharp
public interface IExtensionConfig
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IExtensionConfig.yml" sourcestartlinenumber="1">If you want your extension to be exposed in the backstage's Extensions table, the extension's information needs to be specified in module's &lt;extensionConfig&gt; node in DAML.
If your module needs to load to get the extension's information, your module needs to implement the IExtensionConfig interface.</p>


## Members

### Message

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IExtensionConfig.yml" sourcestartlinenumber="1">Gets or sets the message to appear beside the ProductName in the Extensions table.</p>


```csharp
string Message { get; set; }
```
### ProductName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IExtensionConfig.yml" sourcestartlinenumber="1">Gets or sets the name of the extension as it should appear in the Extensions table.</p>


```csharp
string ProductName { get; set; }
```
### State

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.IExtensionConfig.yml" sourcestartlinenumber="1">Gets or sets the current state of the extension.</p>


```csharp
ExtensionState State { get; set; }
```


