# CIMKnowledgeGraphNamedTypeFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilter.yml" sourcestartlinenumber="1">Base class for Knowledge Graph named type filters.
<remarks>
A named type is either an entity type or a relationship type.<br>
A named type filter represents some instances (entities or relationships) of the named type, and specifies whether these instances are included or excluded.
</remarks></p>


## Object Signature

```csharp
public abstract class CIMKnowledgeGraphNamedTypeFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphNamedTypeFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilter.yml" sourcestartlinenumber="1">Base class for Knowledge Graph named type filters.
<remarks>
A named type is either an entity type or a relationship type.<br>
A named type filter represents some instances (entities or relationships) of the named type, and specifies whether these instances are included or excluded.
</remarks></p>


```csharp
protected CIMKnowledgeGraphNamedTypeFilter()
```
### FilterType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilter.yml" sourcestartlinenumber="1">Gets or sets the filter type, i.e whether to include or exclude the instances represented by the filter.</p>


```csharp
public KGFilterType FilterType { get; set; }
```
### NamedType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilter.yml" sourcestartlinenumber="1">Gets or sets the named type (an entity type or a relationship type).</p>


```csharp
public string NamedType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


