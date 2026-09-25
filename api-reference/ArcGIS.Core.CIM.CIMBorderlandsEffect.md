# CIMBorderlandsEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBorderlandsEffect.yml" sourcestartlinenumber="1">Represents a surface effect for reshading the surface with a borderlands effect in 3D views.</p>


## Object Signature

```csharp
public class CIMBorderlandsEffect : CIMSurfaceEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBorderlandsEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBorderlandsEffect.yml" sourcestartlinenumber="1">Represents a surface effect for reshading the surface with a borderlands effect in 3D views.</p>


```csharp
public CIMBorderlandsEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBorderlandsEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBorderlandsEffect.</p>


```csharp
public CIMBorderlandsEffect Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBorderlandsEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMBorderlandsEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMBorderlandsEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBorderlandsEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBorderlandsEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBorderlandsEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBorderlandsEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


