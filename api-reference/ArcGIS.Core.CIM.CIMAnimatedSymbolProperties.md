# CIMAnimatedSymbolProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Represents animated symbol properties, a collection of symbol properties that apply when the symbol layer has animation data.</p>


## Object Signature

```csharp
public class CIMAnimatedSymbolProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimatedSymbolProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Represents animated symbol properties, a collection of symbol properties that apply when the symbol layer has animation data.</p>


```csharp
public CIMAnimatedSymbolProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimatedSymbolProperties.</p>


```csharp
public CIMAnimatedSymbolProperties Clone()
```
### Duration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets how many seconds it takes to play through the symbol's animation once. This determines a symbol's playback speed.</p>


```csharp
public double Duration { get; set; }
```
### Easing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the animation's easing. Only applicable on non file-based animations.</p>


```csharp
public AnimatedSymbolEasingType Easing { get; set; }
```
### EndingDuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the ending duration of a symbol for time-aware data interpolation. The symbol's playback speed is interpolated linearly from duration to endingDuration over the display period of a time-aware feature.</p>


```csharp
public double EndingDuration { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimatedSymbolProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimatedSymbolProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### PlayAnimation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the animated symbol should play its animation.</p>


```csharp
public bool PlayAnimation { get; set; }
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the primitive name.</p>


```csharp
public string PrimitiveName { get; set; }
```
### RandomizeStartSeed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the starting value for generating a random number. This random number is used by the randomizeStartTime property to determine time offset for each feature.</p>


```csharp
public long RandomizeStartSeed { get; set; }
```
### RandomizeStartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to generate a randomized start offset in seconds to apply to the symbol animation of each feature.</p>


```csharp
public bool RandomizeStartTime { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RepeatDelay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the number of seconds to delay before repeating an animation cycle.</p>


```csharp
public double RepeatDelay { get; set; }
```
### RepeatType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets how to repeat the animation of a symbol when an animation cycle ends.</p>


```csharp
public AnimatedSymbolRepeatType RepeatType { get; set; }
```
### ReverseAnimation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the animated symbol should playback in reverse.</p>


```csharp
public bool ReverseAnimation { get; set; }
```
### StartTimeOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the time offset in seconds to use as the starting point of the symbol animation. This is used if randomizeStartTime=false.</p>


```csharp
public double StartTimeOffset { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimatedSymbolProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseEndingDuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the ending duration of a symbol for time-aware data interpolation.</p>


```csharp
public bool UseEndingDuration { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimatedSymbolProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


