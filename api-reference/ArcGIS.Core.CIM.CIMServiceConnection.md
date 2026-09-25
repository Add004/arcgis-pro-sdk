# CIMServiceConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceConnection.yml" sourcestartlinenumber="1">Represents a service connection.</p>


## Object Signature

```csharp
public abstract class CIMServiceConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMServiceConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceConnection.yml" sourcestartlinenumber="1">Represents a service connection.</p>


```csharp
protected CIMServiceConnection()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


