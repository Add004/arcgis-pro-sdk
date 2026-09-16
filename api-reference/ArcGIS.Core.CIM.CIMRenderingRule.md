# CIMRenderingRule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Represents a raster rendering rule.</p>


## Object Signature

```csharp
public class CIMRenderingRule : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRenderingRule()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Represents a raster rendering rule.</p>


```csharp
public CIMRenderingRule()
```
### Arguments

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Gets or sets the rendering rule arguments as a property set.</p>


```csharp
public IDictionary<string, object> Arguments { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRenderingRule.</p>


```csharp
public CIMRenderingRule Clone()
```
### Definition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Gets or sets the rendering rule definition.</p>


```csharp
public string Definition { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Gets or sets the rendering rule description.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Reconstructs the CIMRenderingRule with a specified state from a JSON encoding.</p>


```csharp
public static CIMRenderingRule FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Gets or sets the rendering rule name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRenderingRule and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VariableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Gets or sets the rendering rule variable name.</p>


```csharp
public string VariableName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRenderingRule.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


