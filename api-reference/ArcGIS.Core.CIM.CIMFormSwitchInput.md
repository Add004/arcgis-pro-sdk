# CIMFormSwitchInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Represents a binary switch, or toggle, form input. This should be used when
selecting between two options.</p>


## Object Signature

```csharp
public class CIMFormSwitchInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormSwitchInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Represents a binary switch, or toggle, form input. This should be used when
selecting between two options.</p>


```csharp
public CIMFormSwitchInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormSwitchInput.</p>


```csharp
public CIMFormSwitchInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormSwitchInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormSwitchInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### OffValueAsLong

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Gets or sets the coded value when switch state is 'off'.</p>


```csharp
public long OffValueAsLong { get; set; }
```
### OffValueAsString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Gets or sets the coded value when switch state is 'off'.</p>


```csharp
public string OffValueAsString { get; set; }
```
### OnValueAsLong

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Gets or sets the coded value when switch state is 'on'.</p>


```csharp
public long OnValueAsLong { get; set; }
```
### OnValueAsString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Gets or sets the coded value when switch state is 'on'.</p>


```csharp
public string OnValueAsString { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormSwitchInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSwitchInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


