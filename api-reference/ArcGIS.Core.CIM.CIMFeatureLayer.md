# CIMFeatureLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureLayer.yml" sourcestartlinenumber="1">Represents a layer that draws data from feature classes.</p>


## Object Signature

```csharp
public class CIMFeatureLayer : CIMGeoFeatureLayerBase, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```

## Remarks

<p>
    A feature layer displays a set of geographic features.
    </p>
<p>
    A geographic feature represents a real-world object on the earth. It has a spatially-referenced location, stored as a point, line, or polygon, and a set of attributes that describe the feature. Its position is accurate and relevant within a particular scale range. Geographic features are the core spatial data holdings of an organization. They can serve as official records, are used in spatial analysis, and are used as source data for cartography.
    </p>
<p>
    Feature layers draw their features by using a feature renderer to transform the geographic feature into one or more graphic entities. Feature renderers read the feature's geometry and attribute values to generate graphic entities that graphically depict the feature on a map.
    </p>


## Members

### CIMFeatureLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureLayer.yml" sourcestartlinenumber="1">Represents a layer that draws data from feature classes.</p>


```csharp
public CIMFeatureLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFeatureLayer.</p>


```csharp
public CIMFeatureLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMFeatureLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMFeatureLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFeatureLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


