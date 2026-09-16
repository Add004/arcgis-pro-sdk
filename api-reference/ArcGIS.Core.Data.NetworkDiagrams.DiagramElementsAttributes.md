# DiagramElementsAttributes

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes.yml" sourcestartlinenumber="1">Represents attributes of diagram elements and their aggregated elements.</p>


## Object Signature

```csharp
public sealed class DiagramElementsAttributes
```


## Members

### DiagramElementsAttributes(string[], List&lt;DiagramElementAttributeValues&gt;, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public DiagramElementsAttributes(string[] attributeNames, List<DiagramElementAttributeValues> attributeValuesPerElement, bool useCodedValueNames)
```
### AttributeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes.yml" sourcestartlinenumber="1">Gets the readonly collection of attribute names used in the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyCollection<string> AttributeNames { get; }
```
### AttributeValuesPerElement

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes.yml" sourcestartlinenumber="1">Gets the <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElementAttributeValues" data-throw-if-not-resolved="false"></xref> in the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<DiagramElementAttributeValues> AttributeValuesPerElement { get; }
```
### UseCodedValueNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes.yml" sourcestartlinenumber="1">Indicates whether attribute values are using coded value names in the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramElementsAttributes" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool UseCodedValueNames { get; }
```


