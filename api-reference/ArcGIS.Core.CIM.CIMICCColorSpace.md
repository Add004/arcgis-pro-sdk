# CIMICCColorSpace

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">Represents a color space defined by an International Color Consortium (ICC) color profile.</p>


## Object Signature

```csharp
public class CIMICCColorSpace : CIMColorSpace, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">A color space defined by an International Color Consortium (ICC) color profile.</p>


## Members

### CIMICCColorSpace()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">Represents a color space defined by an International Color Consortium (ICC) color profile.</p>


```csharp
public CIMICCColorSpace()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">Creates a deep copy of CIMICCColorSpace.</p>


```csharp
public CIMICCColorSpace Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">Reconstructs the CIMICCColorSpace with a specified state from a JSON encoding.</p>


```csharp
public static CIMICCColorSpace FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMICCColorSpace and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">Gets or sets the URL of short name of the color space definition.</p>


```csharp
public string URL { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMICCColorSpace.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


