# CIMEditingTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Represents an editing template.</p>


## Object Signature

```csharp
public abstract class CIMEditingTemplate : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMEditingTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Represents an editing template.</p>


```csharp
protected CIMEditingTemplate()
```
### DefaultToolGUID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Gets or sets the default tool GUID.</p>


```csharp
public string DefaultToolGUID { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### ExcludedToolGUIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Gets or sets the excluded tool GUIDs.</p>


```csharp
public string[] ExcludedToolGUIDs { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Gets or sets the tags.</p>


```csharp
public string Tags { get; set; }
```
### ToolOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Gets or sets the per-tool options.</p>


```csharp
public CIMEditingTemplateToolOptions[] ToolOptions { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplate.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


