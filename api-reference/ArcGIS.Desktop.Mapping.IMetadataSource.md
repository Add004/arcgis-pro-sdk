# IMetadataSource

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMetadataSource.yml" sourcestartlinenumber="1">Indicates if metadata can be retrieved from a source (other than
itself - eg an underlying dataset)</p>


## Object Signature

```csharp
public interface IMetadataSource
```


## Members

### GetUseSourceMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMetadataSource.yml" sourcestartlinenumber="1">Gets whether an underlying source is being used for metadata</p>


```csharp
bool GetUseSourceMetadata()
```
### SetUseSourceMetadata(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMetadataSource.yml" sourcestartlinenumber="1">Set to true to use the underlying source object's metadata</p>


```csharp
void SetUseSourceMetadata(bool useSource)
```


