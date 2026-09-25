# CIMKnowledgeGraphInvestigationTypeInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Investigation Type Info.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphInvestigationTypeInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphInvestigationTypeInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Investigation Type Info.</p>


```csharp
public CIMKnowledgeGraphInvestigationTypeInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphInvestigationTypeInfo.</p>


```csharp
public CIMKnowledgeGraphInvestigationTypeInfo Clone()
```
### DisplayExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Gets or sets the expression information used to create the display name for members of the type.</p>


```csharp
public CIMExpressionInfo DisplayExpressionInfo { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphInvestigationTypeInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphInvestigationTypeInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### PopupInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Gets or sets the pop-up info.</p>


```csharp
public CIMPopupInfo PopupInfo { get; set; }
```
### PropertyInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Gets or sets the array of Knowledge Graph Type Property Infos.
All infos are expected to have unique property name.</p>


```csharp
public CIMKnowledgeGraphTypePropertyInfo[] PropertyInfos { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Gets or sets the symbol for the type.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphInvestigationTypeInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Gets or sets the name of the type.</p>


```csharp
public string TypeName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigationTypeInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


