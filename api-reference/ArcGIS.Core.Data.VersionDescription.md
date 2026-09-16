# VersionDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.VersionDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create or alter a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class VersionDescription
```


## Members

### VersionDescription()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.VersionDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>VersionDescription</code> class.</p>


```csharp
public VersionDescription()
```
### VersionDescription(string, string, VersionAccessType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.VersionDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>VersionDescription</code> class.</p>


```csharp
public VersionDescription(string name, string description, VersionAccessType accessType)
```
### AccessType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VersionDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.VersionAccessType" data-throw-if-not-resolved="false"></xref> for the version.</p>


```csharp
public VersionAccessType AccessType { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VersionDescription.yml" sourcestartlinenumber="1">Gets or sets the version description.</p>


```csharp
public string Description { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VersionDescription.yml" sourcestartlinenumber="1">Gets or sets the version name.</p>


```csharp
public string Name { get; set; }
```


