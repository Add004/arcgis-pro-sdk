# AnimationTransition

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.AnimationTransition.yml" sourcestartlinenumber="1">Specifies the method of transition for a value in a keyframe.</p>


## Object Signature

```csharp
public enum AnimationTransition
```


## Members

### AdjustableArc

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AnimationTransition.yml" sourcestartlinenumber="1">Value changes along a smooth curve to the end state. The tightness of the curve can be configured.</p>


```csharp
AdjustableArc = 5
```
### FixedArc

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AnimationTransition.yml" sourcestartlinenumber="1">Value changes along a tightly controlled curve to the end state.</p>


```csharp
FixedArc = 4
```
### Hold

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AnimationTransition.yml" sourcestartlinenumber="1">Value remains constant, equaling the previous keyframe's value.</p>


```csharp
Hold = 6
```
### Hop

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AnimationTransition.yml" sourcestartlinenumber="1">Value increases, using a parabolic curve, beyond the end state before returning back to it. The height of the curve can be configured.</p>


```csharp
Hop = 3
```
### Linear

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AnimationTransition.yml" sourcestartlinenumber="1">Value changes at a constant (linear) rate to the end state.</p>


```csharp
Linear = 1
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AnimationTransition.yml" sourcestartlinenumber="1">The keyframe value is ignored.</p>


```csharp
None = 0
```
### Stepped

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AnimationTransition.yml" sourcestartlinenumber="1">Value switches to the end state at a specified point along the transition.</p>


```csharp
Stepped = 2
```


