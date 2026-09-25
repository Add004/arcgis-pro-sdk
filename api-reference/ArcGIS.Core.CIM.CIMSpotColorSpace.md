# CIMSpotColorSpace

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Represents a color space for spot colors.</p>


## Object Signature

```csharp
public class CIMSpotColorSpace : CIMColorSpace, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMSpotColorSpace>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">A color space defined for spot colors including alternate and book colors.</p>


## Members

### CIMSpotColorSpace()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Represents a color space for spot colors.</p>


```csharp
public CIMSpotColorSpace()
```
### AlternativeColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Gets or sets the standard (non-spot) color that is used to display the color on-screen.</p>


```csharp
public CIMColor AlternativeColor { get; set; }
```
### BookColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Gets or sets the if present, the color used during output.</p>


```csharp
public CIMColor BookColor { get; set; }
```
### BookID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Gets or sets the ID of the book the color name belongs to.</p>


```csharp
public string BookID { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSpotColorSpace.</p>


```csharp
public CIMSpotColorSpace Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Gets or sets a description of the ink. This can provide more information than the name.</p>


```csharp
public string Description { get; set; }
```
### Equals(CIMSpotColorSpace)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.CIM.CIMSpotColorSpace" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public bool Equals(CIMSpotColorSpace other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.CIM.CIMSpotColorSpace" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public override bool Equals(object other)
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Reconstructs the CIMSpotColorSpace with a specified state from a JSON encoding.</p>


```csharp
public static CIMSpotColorSpace FromJson(string json, JsonDeserializationSettings settings = null)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Gets a hash code for the current object.</p>


```csharp
public override int GetHashCode()
```
### IsReferencedColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the color is a referenced color. When this property is true, the alternative color will be looked up from the color book based on the BookID and Name.</p>


```csharp
public bool IsReferencedColor { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Gets or sets the defined ink name for the spot color. Usually this is a well-known color standard name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSpotColorSpace and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### operator ==(CIMSpotColorSpace, CIMSpotColorSpace)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">sp1</code> and <code class="paramref">sp2</code> are equal.</p>


```csharp
public static bool operator ==(CIMSpotColorSpace sp1, CIMSpotColorSpace sp2)
```
### operator !=(CIMSpotColorSpace, CIMSpotColorSpace)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColorSpace.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">sp1</code> and <code class="paramref">sp2</code> are not equal.</p>


```csharp
public static bool operator !=(CIMSpotColorSpace sp1, CIMSpotColorSpace sp2)
```


