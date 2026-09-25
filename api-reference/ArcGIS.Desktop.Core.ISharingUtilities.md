# ISharingUtilities

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll


## Object Signature

```csharp
public interface ISharingUtilities
```


## Members

### CompactWhitespaces(string, bool)

- Kind: method


```csharp
string CompactWhitespaces(string s, bool fullCompact = false)
```
### GetInvalidCharsInName(string, bool, bool, bool, bool)

- Kind: method


```csharp
string GetInvalidCharsInName(string fileName, bool isServiceName = false, bool isServerFolder = false, bool isMapServiceName = false, bool isWebMap = false)
```
### GetInvalidCharsInNameForPortalProjects(string, bool, bool, bool, bool)

- Kind: method


```csharp
string GetInvalidCharsInNameForPortalProjects(string fileName, bool isServiceName = false, bool isServerFolder = false, bool isMapServiceName = false, bool isWebMap = false)
```
### IsValidFileName(string, bool, bool, bool, bool, bool, bool)

- Kind: method


```csharp
bool IsValidFileName(string fileName, bool isServiceName = false, bool isOverwriteFolder = false, bool forPackaging = true, bool isServerFolder = false, bool isMapServiceName = false, bool isWebMap = false)
```
### IsValidFileNameForPortalProjects(string, bool, bool, bool, bool, bool, bool)

- Kind: method


```csharp
bool IsValidFileNameForPortalProjects(string fileName, bool isServiceName = false, bool isOverwriteFolder = false, bool forPackaging = true, bool isServerFolder = false, bool isMapServiceName = false, bool isWebMap = false)
```


