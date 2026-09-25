# CIMBindVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBindVariable.yml" sourcestartlinenumber="1">Represents a bind variable.</p>


## Object Signature

```csharp
public abstract class CIMBindVariable : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBindVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBindVariable.yml" sourcestartlinenumber="1">Represents a bind variable.</p>


```csharp
protected CIMBindVariable()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBindVariable.yml" sourcestartlinenumber="1">Gets or sets the alias of the variable.</p>


```csharp
public string Alias { get; set; }
```
### DataType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBindVariable.yml" sourcestartlinenumber="1">Gets or sets the type of the variable.</p>


```csharp
public BindVariableType DataType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBindVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### VariableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBindVariable.yml" sourcestartlinenumber="1">Gets or sets the name of the variable. The name must be unique among all variables.</p>


```csharp
public string VariableName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBindVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


