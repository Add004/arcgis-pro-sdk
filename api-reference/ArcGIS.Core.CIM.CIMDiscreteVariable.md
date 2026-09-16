# CIMDiscreteVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Represents a single bind variable.</p>


## Object Signature

```csharp
public class CIMDiscreteVariable : CIMBindVariable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDiscreteVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Represents a single bind variable.</p>


```csharp
public CIMDiscreteVariable()
```
### AllowMultiple

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the variable will accept an array of values.</p>


```csharp
public bool AllowMultiple { get; set; }
```
### BoundValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Gets or sets the variable's currently-bound value. The array can have multiple values only if AllowMultiple is true.</p>


```csharp
public object[] BoundValue { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDiscreteVariable.</p>


```csharp
public CIMDiscreteVariable Clone()
```
### DefaultValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Gets or sets the variable's required default value. The array can have multiple values only if AllowMultiple is true.</p>


```csharp
public object[] DefaultValue { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMDiscreteVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMDiscreteVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDiscreteVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDiscreteVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


