# CIMDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Represents an object with a unique identity within a CIM project or document.</p>


## Object Signature

```csharp
public abstract class CIMDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Represents an object with a unique identity within a CIM project or document.</p>


```csharp
protected CIMDefinition()
```
### MetadataURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Gets or sets the metadata URI.</p>


```csharp
public string MetadataURI { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceModifiedTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Gets or sets the time the source was last modified, as of the last sync. Used to detect when another sync is needed.</p>


```csharp
public TimeInstant SourceModifiedTime { get; set; }
```
### SourcePortalUrl

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Gets or sets the source portal URI of the item. Set if sourced from an external item such as an item on a portal.</p>


```csharp
public string SourcePortalUrl { get; set; }
```
### SourceURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Gets or sets the source URI of the item. Set if sourced from an external item such as an item on a portal.</p>


```csharp
public string SourceURI { get; set; }
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Gets or sets the URI of the definition. Typically set by the system and used as an identifier.</p>


```csharp
public string URI { get; set; }
```
### UseSourceMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the CIM definition accesses metadata from its data source (the default behavior), or if it has its own metadata stored in the project.</p>


```csharp
public bool UseSourceMetadata { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


