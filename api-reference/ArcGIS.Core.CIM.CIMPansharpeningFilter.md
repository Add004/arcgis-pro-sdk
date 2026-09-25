# CIMPansharpeningFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Represents a pansharpening filter.</p>


## Object Signature

```csharp
public class CIMPansharpeningFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPansharpeningFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Represents a pansharpening filter.</p>


```csharp
public CIMPansharpeningFilter()
```
### BWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Gets or sets the blue weight.</p>


```csharp
public double BWeight { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPansharpeningFilter.</p>


```csharp
public CIMPansharpeningFilter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMPansharpeningFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMPansharpeningFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### GWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Gets or sets the green weight.</p>


```csharp
public double GWeight { get; set; }
```
### IWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Gets or sets the infrared weight.</p>


```csharp
public double IWeight { get; set; }
```
### InfraredImage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Gets or sets the data connection of the optional infrared image.</p>


```csharp
public CIMDataConnection InfraredImage { get; set; }
```
### PanImage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Gets or sets the data connection of the optional panchromatic image.</p>


```csharp
public CIMDataConnection PanImage { get; set; }
```
### PansharpeningType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Gets or sets the data connection of the current pansharpening type.</p>


```csharp
public PansharpeningType PansharpeningType { get; set; }
```
### RWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Gets or sets the red weight.</p>


```csharp
public double RWeight { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPansharpeningFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPansharpeningFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


