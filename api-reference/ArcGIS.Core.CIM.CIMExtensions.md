# CIMExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Adds extension methods to ArcGIS.Core.CIM objects.</p>


## Object Signature

```csharp
public static class CIMExtensions
```


## Members

### AddModel(CIMMultipatchFeatureTemplate, Multipatch)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Add a new model to a CIMMultipatchFeatureTemplate.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void AddModel(this CIMMultipatchFeatureTemplate templatedDef, Multipatch modelGeom)
```
### AllowToolID(CIMEditingTemplate, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Allows a construction tool on the template.</p>


```csharp
public static void AllowToolID(this CIMEditingTemplate templateDef, string damlID)
```
### ExcludeToolID(CIMEditingTemplate, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Excludes a construction tool from the template.</p>


```csharp
public static void ExcludeToolID(this CIMEditingTemplate templateDef, string damlID)
```
### GetDefaultToolID(CIMEditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Gets the default construction tool.</p>


```csharp
public static string GetDefaultToolID(this CIMEditingTemplate templateDef)
```
### GetExcludedToolIDs(CIMEditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Gets the excluded construction tools on the template.</p>


```csharp
public static IReadOnlyCollection<string> GetExcludedToolIDs(this CIMEditingTemplate templateDef)
```
### ReadTags(CIMEditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Read the Tags from a CIMEditingTemplate.</p>


```csharp
public static IReadOnlyCollection<string> ReadTags(this CIMEditingTemplate templateDef)
```
### SetDefaultToolID(CIMEditingTemplate, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Sets the default construction tool.</p>


```csharp
public static void SetDefaultToolID(this CIMEditingTemplate templateDef, string damlID)
```
### SetExcludedToolIDs(CIMEditingTemplate, string[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Sets the excluded construction tools on the template.</p>


```csharp
public static void SetExcludedToolIDs(this CIMEditingTemplate templateDef, string[] damlIDs)
```
### WriteTags(CIMEditingTemplate, IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExtensions.yml" sourcestartlinenumber="1">Write an array of tags to a CIMEditingTemplate.</p>


```csharp
public static void WriteTags(this CIMEditingTemplate templateDef, IEnumerable<string> tags)
```


