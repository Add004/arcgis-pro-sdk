# AssociationDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Represents a connectivity (spatial and non-spatial), containment, or structural attachment association in a utility network.</p>


## Object Signature

```csharp
public sealed class AssociationDescription
```


## Members

### AssociationDescription(AssociationType, RowHandle, RowHandle)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Creates a new utility network AssociationDescription of the specified type.  Use this constructor for</p>
<ul><li>
Structural attachment associations (<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Attachment" data-throw-if-not-resolved="false"></xref>).
</li><li>
Connectivity associations (<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionJunctionConnectivity" data-throw-if-not-resolved="false"></xref>).
</li><li>
Junction-edge "from side" object connectivity associations (<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityFromSide" data-throw-if-not-resolved="false"></xref>).
</li><li>
Junction-edge "to side" object connectivity associations (<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityToSide" data-throw-if-not-resolved="false"></xref>).
</li></ul>


```csharp
public AssociationDescription(AssociationType type, RowHandle row1, RowHandle row2)
```
### AssociationDescription(AssociationType, RowHandle, RowHandle, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Creates a new utility network AssociationDescription of the specified type. Use this constructor for containment associations only
(<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Containment" data-throw-if-not-resolved="false"></xref>).</p>


```csharp
public AssociationDescription(AssociationType type, RowHandle row1, RowHandle row2, bool isContainmentVisible)
```
### AssociationDescription(AssociationType, RowHandle, RowHandle, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Creates a new utility network AssociationDescription of the specified type.  Use this constructor for junction-edge <b>midspan</b> object connectivity
associations only (<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityMidspan" data-throw-if-not-resolved="false"></xref>).</p>


```csharp
public AssociationDescription(AssociationType type, RowHandle row1, RowHandle row2, double percentAlong)
```
### AssociationDescription(AssociationType, RowHandle, RowHandle, long)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Creates a new utility network AssociationDescription of the specified type.  Use this constructor for connectivity associations only
(<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionJunctionConnectivity" data-throw-if-not-resolved="false"></xref>).</p>


```csharp
public AssociationDescription(AssociationType type, RowHandle row1, RowHandle row2, long terminalID2)
```
### AssociationDescription(AssociationType, RowHandle, long, RowHandle)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Creates a new utility network AssociationDescription of the specified type.  Use this constructor for</p>
<ul><li>
Connectivity associations (<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionJunctionConnectivity" data-throw-if-not-resolved="false"></xref>).
</li><li>
Junction-edge "from side" object connectivity associations (<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityFromSide" data-throw-if-not-resolved="false"></xref>).
</li><li>
Junction-edge "to side" object connectivity associations (<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityToSide" data-throw-if-not-resolved="false"></xref>).
</li></ul>


```csharp
public AssociationDescription(AssociationType type, RowHandle row1, long terminalID1, RowHandle row2)
```
### AssociationDescription(AssociationType, RowHandle, long, RowHandle, long)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Creates a new utility network AssociationDescription of the specified type.  Use this constructor for connectivity associations only
(<code class="paramref">type</code> is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionJunctionConnectivity" data-throw-if-not-resolved="false"></xref>).</p>


```csharp
public AssociationDescription(AssociationType type, RowHandle row1, long terminalID1, RowHandle row2, long terminalID2)
```
### AssociationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Gets the association type between <xref href="ArcGIS.Desktop.Editing.AssociationDescription.Row1" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.AssociationDescription.Row2" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AssociationType AssociationType { get; }
```
### IsContentVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Gets a value indicating whether the content in the map is visible when outside of a container view if this <code>Association</code> represents a
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Containment" data-throw-if-not-resolved="false"></xref> association.
For all other AssociationTypes the value is False.</p>


```csharp
public bool IsContentVisible { get; }
```
### PercentAlong

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Gets the percent along the midspan of a non-spatial edge object that a junction or non-spatial junction object
is connected to if this <code>Association</code> represents a <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityMidspan" data-throw-if-not-resolved="false"></xref> association.
For all other AssociationTypes the value is null.</p>


```csharp
public double? PercentAlong { get; }
```
### Row1

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Gets the first row in the association.</p>
<ul><li>
Represents the "from" object if AssociationType is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionJunctionConnectivity" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the container object if AssociationType is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Containment" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the structure object if AssociationType is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Attachment" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the junction or non-spatial junction object connecting to the <b>from side</b> of the non-spatial edge object if AssociationType is 
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityFromSide" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the junction or non-spatial junction object connecting to the <b>to side</b> of the non-spatial edge object if AssociationType is
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityToSide" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the junction or non-spatial junction object connecting to the <b>midspan</b> of the non-spatial edge object if AssociationType is
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityMidspan" data-throw-if-not-resolved="false"></xref>.
</li></ul>


```csharp
public RowHandle Row1 { get; }
```
### Row2

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">Gets the second row in the association.</p>
<ul><li>
Represents the "to" object if AssociationType is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionJunctionConnectivity" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the content object if AssociationType is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Containment" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the attached object if AssociationType is <xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.Attachment" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the non-spatial edge object connecting to its <b>from side</b> by a junction or non-spatial junction object if AssociationType is 
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityFromSide" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the non-spatial edge object connecting to its <b>to side</b> by a junction or non-spatial junction object if AssociationType is
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityToSide" data-throw-if-not-resolved="false"></xref>.
</li><li>
Represents the non-spatial edge object connecting <b>midspan</b> to a junction or non-spatial junction object if AssociationType is
<xref href="ArcGIS.Core.Data.UtilityNetwork.AssociationType.JunctionEdgeObjectConnectivityMidspan" data-throw-if-not-resolved="false"></xref>.
</li></ul>


```csharp
public RowHandle Row2 { get; }
```
### Terminal1

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">If the first row represents a device with terminals, the terminal on the first row to connect. Otherwise the value is -1.</p>


```csharp
public long Terminal1 { get; }
```
### Terminal2

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AssociationDescription.yml" sourcestartlinenumber="1">If the second row represents a device with terminals, the terminal on the second row to connect.  Otherwise the value is -1.</p>


```csharp
public long Terminal2 { get; }
```


