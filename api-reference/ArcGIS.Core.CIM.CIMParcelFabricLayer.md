# CIMParcelFabricLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Represents a parcel fabric layer.</p>


## Object Signature

```csharp
public class CIMParcelFabricLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMParcelFabricLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Represents a parcel fabric layer.</p>


```csharp
public CIMParcelFabricLayer()
```
### AccuracyTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the accuracy table.</p>


```csharp
public string AccuracyTable { get; set; }
```
### AdjustmentsTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the adjustments table.</p>


```csharp
public string AdjustmentsTable { get; set; }
```
### AllLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the paths of the layers in the parcel fabric layer.</p>


```csharp
public string[] AllLayers { get; set; }
```
### CadastralFabricConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection to the fabric.</p>


```csharp
public CIMDataConnection CadastralFabricConnection { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMParcelFabricLayer.</p>


```csharp
public CIMParcelFabricLayer Clone()
```
### ControlPointLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the control point layer.</p>


```csharp
public string ControlPointLayer { get; set; }
```
### ControlPointSelectionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the control point selection symbol.</p>


```csharp
public CIMSymbolReference ControlPointSelectionSymbol { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMParcelFabricLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMParcelFabricLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### JobsTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the jobs table.</p>


```csharp
public string JobsTable { get; set; }
```
### LineLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the line layer.</p>


```csharp
public string LineLayer { get; set; }
```
### LinePointLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the line point layer.</p>


```csharp
public string LinePointLayer { get; set; }
```
### ParcelLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the parcel layer.</p>


```csharp
public string ParcelLayer { get; set; }
```
### PlansTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the plans table.</p>


```csharp
public string PlansTable { get; set; }
```
### PointLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the point layer.</p>


```csharp
public string PointLayer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMParcelFabricLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


