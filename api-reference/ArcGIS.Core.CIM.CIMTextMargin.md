# CIMTextMargin

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Represents a text margin which defines the margin to apply around text.</p>


## Object Signature

```csharp
public class CIMTextMargin : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTextMargin()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Represents a text margin which defines the margin to apply around text.</p>


```csharp
public CIMTextMargin()
```
### Bottom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Gets or sets the bottom margin.</p>


```csharp
public double Bottom { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTextMargin.</p>


```csharp
public CIMTextMargin Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Reconstructs the CIMTextMargin with a specified state from a JSON encoding.</p>


```csharp
public static CIMTextMargin FromJson(string json, JsonDeserializationSettings settings = null)
```
### Left

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Gets or sets the left margin.</p>


```csharp
public double Left { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Right

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Gets or sets the right margin.</p>


```csharp
public double Right { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTextMargin and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Top

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Gets or sets the top margin.</p>


```csharp
public double Top { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextMargin.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


