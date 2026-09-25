# CIMLabelClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Represents a label class which describes how to generate a set of text labels from a group of features in a feature layer.</p>


## Object Signature

```csharp
public class CIMLabelClass : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLabelClass()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Represents a label class which describes how to generate a set of text labels from a group of features in a feature layer.</p>


```csharp
public CIMLabelClass()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLabelClass.</p>


```csharp
public CIMLabelClass Clone()
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the label expression.</p>


```csharp
public string Expression { get; set; }
```
### ExpressionEngine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the label expression engine (the language the expression is written in).</p>


```csharp
public LabelExpressionEngine ExpressionEngine { get; set; }
```
### ExpressionTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the human readable text title that describes the label expression.</p>


```csharp
public string ExpressionTitle { get; set; }
```
### FeaturesToLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets a parameter indicating which features to label.</p>


```csharp
public FeaturesToLabel FeaturesToLabel { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Reconstructs the CIMLabelClass with a specified state from a JSON encoding.</p>


```csharp
public static CIMLabelClass FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the ID of the label class. This property is only used in the context of annotation.</p>


```csharp
public int ID { get; set; }
```
### MaplexLabelPlacementProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the Maplex placement properties which are used when the map uses the Maplex label engine.</p>


```csharp
public CIMMaplexLabelPlacementProperties MaplexLabelPlacementProperties { get; set; }
```
### MaximumScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the maximum scale for labeling (set as the denominator of the scale's representative fraction).</p>


```csharp
public double MaximumScale { get; set; }
```
### MinimumScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the minimum scale for labeling (set as the denominator of the scale's representative fraction).</p>


```csharp
public double MinimumScale { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the name of the label class.</p>


```csharp
public string Name { get; set; }
```
### Priority

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the priority of the label class.</p>


```csharp
public int Priority { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandardLabelPlacementProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the standard placement properties which are used when the map uses the standard label engine.</p>


```csharp
public CIMStandardLabelPlacementProperties StandardLabelPlacementProperties { get; set; }
```
### TextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the text symbol of the label class.</p>


```csharp
public CIMSymbolReference TextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLabelClass and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseCodedValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use coded value domain descriptions when labeling.</p>


```csharp
public bool UseCodedValue { get; set; }
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this label class is visible.</p>


```csharp
public bool Visibility { get; set; }
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Gets or sets the SQL where clause of which features to label with this label class.</p>


```csharp
public string WhereClause { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLabelClass.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


