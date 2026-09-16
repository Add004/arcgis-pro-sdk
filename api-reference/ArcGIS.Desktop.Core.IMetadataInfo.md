# IMetadataInfo

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadataInfo.yml" sourcestartlinenumber="1">Supports access and update of metadata</p>


## Object Signature

```csharp
public interface IMetadataInfo
```


## Members

### GetCanEditMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadataInfo.yml" sourcestartlinenumber="1">Check whether the metadata can be edited</p>


```csharp
bool GetCanEditMetadata()
```
### GetMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadataInfo.yml" sourcestartlinenumber="1">Get the metadata xml</p>


```csharp
string GetMetadata()
```
### SetMetadata(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadataInfo.yml" sourcestartlinenumber="1">Set the metadata xml.</p>


```csharp
void SetMetadata(string metadataXml)
```


