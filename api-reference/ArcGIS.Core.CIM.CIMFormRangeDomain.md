# CIMFormRangeDomain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Represents a domain that specifies a range of valid values for a field.</p>


## Object Signature

```csharp
public class CIMFormRangeDomain : CIMFormDomain, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormRangeDomain()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Represents a domain that specifies a range of valid values for a field.</p>


```csharp
public CIMFormRangeDomain()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormRangeDomain.</p>


```csharp
public CIMFormRangeDomain Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Reconstructs the CIMFormRangeDomain with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormRangeDomain FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Gets or sets the domain name.</p>


```csharp
public string Name { get; set; }
```
### Range

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Gets or sets the range of valid values. The first element is the minValue and the second element is the maxValue.</p>


```csharp
public double[] Range { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormRangeDomain and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRangeDomain.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


