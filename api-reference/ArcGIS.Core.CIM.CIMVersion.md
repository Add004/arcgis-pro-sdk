# CIMVersion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVersion.yml" sourcestartlinenumber="1">Represents a version object used for representing the saved version.</p>


## Object Signature

```csharp
public abstract class CIMVersion : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVersion()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVersion.yml" sourcestartlinenumber="1">Represents a version object used for representing the saved version.</p>


```csharp
protected CIMVersion()
```
### Build

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVersion.yml" sourcestartlinenumber="1">Gets or sets the build an item was created with. Set by the system.</p>


```csharp
public int Build { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVersion.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Version

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVersion.yml" sourcestartlinenumber="1">Gets or sets document version. Set by the system.</p>


```csharp
public string Version { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVersion.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


