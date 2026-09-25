# CIMHuffModelAttractivenessVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Represents attractiveness variable used in Huff Model.</p>


## Object Signature

```csharp
public class CIMHuffModelAttractivenessVariable : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHuffModelAttractivenessVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Represents attractiveness variable used in Huff Model.</p>


```csharp
public CIMHuffModelAttractivenessVariable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHuffModelAttractivenessVariable.</p>


```csharp
public CIMHuffModelAttractivenessVariable Clone()
```
### Exponent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Gets or sets the exponent of the variable.</p>


```csharp
public double Exponent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMHuffModelAttractivenessVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMHuffModelAttractivenessVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Gets or sets the name of the variable.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHuffModelAttractivenessVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelAttractivenessVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


