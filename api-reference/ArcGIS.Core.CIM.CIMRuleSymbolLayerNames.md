# CIMRuleSymbolLayerNames

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Represents rule symbol layer names.</p>


## Object Signature

```csharp
public class CIMRuleSymbolLayerNames : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRuleSymbolLayerNames()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Represents rule symbol layer names.</p>


```csharp
public CIMRuleSymbolLayerNames()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRuleSymbolLayerNames.</p>


```csharp
public CIMRuleSymbolLayerNames Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Reconstructs the CIMRuleSymbolLayerNames with a specified state from a JSON encoding.</p>


```csharp
public static CIMRuleSymbolLayerNames FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RuleID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Gets or sets the rule ID.</p>


```csharp
public int RuleID { get; set; }
```
### SymbolLayerNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Gets or sets the symbol layer names.</p>


```csharp
public string[] SymbolLayerNames { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRuleSymbolLayerNames and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRuleSymbolLayerNames.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


