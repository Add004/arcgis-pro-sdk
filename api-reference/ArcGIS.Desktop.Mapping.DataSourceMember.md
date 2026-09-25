# DataSourceMember

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DataSourceMember.yml" sourcestartlinenumber="1">Represents a Data Source node in the &quot;List By Data Source&quot; TOC view</p>


## Object Signature

```csharp
public interface DataSourceMember
```


## Members

### GetMapMembers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DataSourceMember.yml" sourcestartlinenumber="1">Gets a snap-shot collection of MapMembers contained in the node</p>


```csharp
IReadOnlyList<MapMember> GetMapMembers()
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DataSourceMember.yml" sourcestartlinenumber="1">Gets whether the DataSourceMember is valid</p>


```csharp
bool IsValid { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DataSourceMember.yml" sourcestartlinenumber="1">Gets the name of this DataSourceMember as it appears in the TOC.</p>


```csharp
string Name { get; }
```


