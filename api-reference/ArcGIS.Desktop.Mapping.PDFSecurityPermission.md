# PDFSecurityPermission

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">PDF security permissions.</p>


## Object Signature

```csharp
[Flags]
public enum PDFSecurityPermission : uint
```


## Members

### Accessible

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Enable's the Accessibility API.</p>


```csharp
Accessible = 512
```
### All

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Enable permission for everything.</p>


```csharp
All = 4294967295
```
### AllMaster

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Combination of HighPrint, Edit, Copy, EditNotes</p>


```csharp
AllMaster = Edit | Copy | EditNotes | HighPrint
```
### Copy

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows to copy information from PDF document.</p>


```csharp
Copy = 16
```
### DocAssembly

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows to insert/delete/rotate pages and create bookmark and thumbnail.</p>


```csharp
DocAssembly = 1024
```
### Edit

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows to edit PDF document.</p>


```csharp
Edit = 8
```
### EditNotes

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows to edit text notes.</p>


```csharp
EditNotes = 32
```
### FillAndSign

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows to fill in or sign existing form or signatures.</p>


```csharp
FillAndSign = 256
```
### HighPrint

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows High quality printing.</p>


```csharp
HighPrint = 2052
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">No permissions</p>


```csharp
None = 0
```
### Open

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows to open PDF document.</p>


```csharp
Open = 1
```
### Print

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows to print PDF document in low quality.</p>


```csharp
Print = 4
```
### Secure

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows to change PDF document's security.</p>


```csharp
Secure = 2
```
### SpawnTempl

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFSecurityPermission.yml" sourcestartlinenumber="1">Allows page template spawning even if Edit and EditNotes are clear.</p>


```csharp
SpawnTempl = 131072
```


