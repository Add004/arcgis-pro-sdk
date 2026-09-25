# CIMInternetServerConnectionBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Represents the internet server connection base class.</p>


## Object Signature

```csharp
public abstract class CIMInternetServerConnectionBase : CIMServerConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMInternetServerConnectionBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Represents the internet server connection base class.</p>


```csharp
protected CIMInternetServerConnectionBase()
```
### Anonymous

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not this is an anonymous connection.</p>


```csharp
public bool Anonymous { get; set; }
```
### AuthenticationInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Gets or sets the string containing additional authentication information for the connection.</p>


```csharp
public string AuthenticationInfo { get; set; }
```
### HideUserProperty

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to hide the user.</p>


```csharp
public bool HideUserProperty { get; set; }
```
### Password

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Gets or sets the encrypted password as a base 64 encoded string. Used internally by the system. Not persisted in documents.</p>


```csharp
public string Password { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Gets or sets the URL.</p>


```csharp
public string URL { get; set; }
```
### User

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Gets or sets the user.</p>


```csharp
public string User { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInternetServerConnectionBase.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


