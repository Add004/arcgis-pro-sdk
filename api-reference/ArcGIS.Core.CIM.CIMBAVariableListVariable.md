# CIMBAVariableListVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Represents variable of at variable list.</p>


## Object Signature

```csharp
public class CIMBAVariableListVariable : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAVariableListVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Represents variable of at variable list.</p>


```csharp
public CIMBAVariableListVariable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAVariableListVariable.</p>


```csharp
public CIMBAVariableListVariable Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMBAVariableListVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAVariableListVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### Names

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Gets or sets names of the variable.</p>


```csharp
public string[] Names { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAVariableListVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Gets or sets value types of the variable. If null, Number value type is used.</p>


```csharp
public BAVariableListValueType[] ValueTypes { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableListVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


