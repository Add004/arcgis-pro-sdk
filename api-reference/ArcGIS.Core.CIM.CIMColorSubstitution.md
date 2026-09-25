# CIMColorSubstitution

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Represents color substitution, an ordered list of color substitutes.</p>


## Object Signature

```csharp
public class CIMColorSubstitution : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMColorSubstitution()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Represents color substitution, an ordered list of color substitutes.</p>


```csharp
public CIMColorSubstitution()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Creates a deep copy of CIMColorSubstitution.</p>


```csharp
public CIMColorSubstitution Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Reconstructs the CIMColorSubstitution with a specified state from a JSON encoding.</p>


```csharp
public static CIMColorSubstitution FromJson(string json, JsonDeserializationSettings settings = null)
```
### NewColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Gets or sets the new color that will replace the old color.</p>


```csharp
public CIMColor NewColor { get; set; }
```
### OldColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Gets or sets the old color (the color that will be substituted).</p>


```csharp
public CIMColor OldColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMColorSubstitution and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSubstitution.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


