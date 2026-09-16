# LeaderLineStyle

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.LeaderLineStyle.yml" sourcestartlinenumber="1">The style of line to generate when a leader is drawn defined by an enumeration value. Line leaders will always be drawn with their own geometry.</p>


## Object Signature

```csharp
public enum LeaderLineStyle
```


## Members

### Base

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LeaderLineStyle.yml" sourcestartlinenumber="1">The line callout leader is a single line originating from the closest corner of the text box with the gap applied. If the callout has an accent bar it is connected to the closest point at the either top or bottom of the accent bar.</p>


```csharp
Base = 0
```
### CircularCCW

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LeaderLineStyle.yml" sourcestartlinenumber="1">The line callout leader is curved (counter-clockwise) from the anchor point to the closest corner of the text box with the gap applied. If the callout has an accent bar it is connected to the closest point at the either top or bottom of the accent bar.</p>


```csharp
CircularCCW = 6
```
### CircularCW

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LeaderLineStyle.yml" sourcestartlinenumber="1">The line callout leader is curved (clockwise) from the anchor point to the closest corner of the text box with the gap applied. If the callout has an accent bar it is connected to the closest point at the either top or bottom of the accent bar.</p>


```csharp
CircularCW = 5
```
### FourPoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LeaderLineStyle.yml" sourcestartlinenumber="1">The line callout leader is a 4-point line originating from the midpoint of the left or right side of the text box with the gap applied or the midpoint of the accent bar if the callout has one.</p>


```csharp
FourPoint = 3
```
### MidPoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LeaderLineStyle.yml" sourcestartlinenumber="1">The line callout leader is a single line originating from the midpoint of the left or right side of the text box with the gap applied or from the midpoint of the accent bar if the callout has one.</p>


```csharp
MidPoint = 1
```
### ThreePoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LeaderLineStyle.yml" sourcestartlinenumber="1">The line callout leader is a 3-point line originating from the midpoint of the left or right side of the text box with the gap applied or the midpoint of the accent bar if the callout has one.</p>


```csharp
ThreePoint = 2
```
### Underline

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LeaderLineStyle.yml" sourcestartlinenumber="1">The line callout draws a line that connects to the closest of the four corners of the text with the gap applied. If the callout has an accent bar it is connected to the closest point at either the top or bottom of the accent bar. Additionally, either and underline or an &quot;overline&quot; is drawn along the closest side (bottom or top) of the text.</p>


```csharp
Underline = 4
```


