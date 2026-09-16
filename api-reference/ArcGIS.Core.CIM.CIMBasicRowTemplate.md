# CIMBasicRowTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicRowTemplate.yml" sourcestartlinenumber="1">Represents a basic row template.</p>


## Object Signature

```csharp
public abstract class CIMBasicRowTemplate : CIMEditingTemplate, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBasicRowTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicRowTemplate.yml" sourcestartlinenumber="1">Represents a basic row template.</p>


```csharp
protected CIMBasicRowTemplate()
```
### DefaultValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicRowTemplate.yml" sourcestartlinenumber="1">Gets or sets the default values.</p>


```csharp
public IDictionary<string, object> DefaultValues { get; set; }
```
### HiddenFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicRowTemplate.yml" sourcestartlinenumber="1">Gets or sets the hidden fields.</p>


```csharp
public string[] HiddenFields { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicRowTemplate.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Relationships

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicRowTemplate.yml" sourcestartlinenumber="1">Gets or sets the template relationships.</p>


```csharp
public CIMEditingTemplateRelationship[] Relationships { get; set; }
```
### RequiredFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicRowTemplate.yml" sourcestartlinenumber="1">Gets or sets the required fields.</p>


```csharp
public string[] RequiredFields { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicRowTemplate.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


