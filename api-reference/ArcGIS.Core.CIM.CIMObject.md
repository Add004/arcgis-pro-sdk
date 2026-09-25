# CIMObject

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Represents the base CIM object class.</p>


## Object Signature

```csharp
public abstract class CIMObject : INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMObject()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Represents the base CIM object class.</p>


```csharp
protected CIMObject()
```
### Clone(CIMObject)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Creates a deep copy of the CIMObject.</p>


```csharp
public static CIMObject Clone(CIMObject objectToClone)
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Reconstructs the CIMObject with a specified state from a JSON encoding.</p>


```csharp
public static CIMObject FromJson(string json, JsonDeserializationSettings settings = null)
```
### GetSchema()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Not implemented, reserved for future use.</p>


```csharp
public XmlSchema GetSchema()
```
### PropertyChanged

- Kind: event

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Occurs when a property value changes.</p>


```csharp
public event PropertyChangedEventHandler PropertyChanged
```
### RaisePropertyChanged(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Called from a property setter to notify the framework that an Object member has changed.</p>


```csharp
protected void RaisePropertyChanged(string propertyName)
```
### ReadXml(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Reads the element inside the reader.</p>


```csharp
public void ReadXml(XmlReader reader)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Reads the current element from the reader. Returns 'True' if the EndElement node was read by the function.</p>


```csharp
protected virtual bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMObject and its current state.</p>


```csharp
public virtual string ToJson(JsonSerializationSettings settings = null)
```
### WriteXml(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Writes the element inside the writer.</p>


```csharp
public void WriteXml(XmlWriter writer)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject.yml" sourcestartlinenumber="1">Writes the elements to xml writer</p>


```csharp
protected virtual void WriteXmlElements(XmlWriter writer)
```


