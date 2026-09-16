# CIMLayerAction

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Represents a layer action.</p>


## Object Signature

```csharp
[Obsolete("CIMLayerAction is deprecated at 3.4. ")]
public class CIMLayerAction : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLayerAction()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Represents a layer action.</p>


```csharp
public CIMLayerAction()
```
### Activities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Gets or sets activities.</p>


```csharp
public CIMActivity[] Activities { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLayerAction.</p>


```csharp
public CIMLayerAction Clone()
```
### Conditions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Gets or sets conditions.</p>


```csharp
public CIMCondition[] Conditions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Reconstructs the CIMLayerAction with a specified state from a JSON encoding.</p>


```csharp
public static CIMLayerAction FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLayerAction and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerAction.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


