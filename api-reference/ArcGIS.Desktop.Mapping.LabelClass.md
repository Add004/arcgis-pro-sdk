# LabelClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Represents a label class with labeling properties for a defined collection of features.</p>


## Object Signature

```csharp
public class LabelClass : PropertyChangedBase
```


## Members

### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the label expression of the label class.</p>


```csharp
public string Expression { get; }
```
### ExpressionEngine

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the label expression engine of the label class.</p>


```csharp
public LabelExpressionEngine ExpressionEngine { get; }
```
### FeatureLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the feature layer that the label class belongs to, when applicable.</p>


```csharp
public FeatureLayer FeatureLayer { get; }
```
### GetMaplexLabelPlacementProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Returns the maplex label placement properties definition of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMaplexLabelPlacementProperties GetMaplexLabelPlacementProperties()
```
### GetStandardLabelPlacementProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Returns a standard label placement properties definition of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMStandardLabelPlacementProperties GetStandardLabelPlacementProperties()
```
### GetTextSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Returns the text symbol definition that the label class belongs to.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol GetTextSymbol()
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the layer that the label class belongs to.</p>


```csharp
public Layer Layer { get; }
```
### MaximumScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the maximum scale of the label class.</p>


```csharp
public double MaximumScale { get; }
```
### MinimumScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the minimum scale of the label class.</p>


```csharp
public double MinimumScale { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the name of the label class.</p>


```csharp
public string Name { get; }
```
### Priority

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the priority of the label class.</p>


```csharp
public int Priority { get; }
```
### SetExpression(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the label expression of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpression(string expression)
```
### SetExpressionEngine(LabelExpressionEngine)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the expression engine of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpressionEngine(LabelExpressionEngine expressionEngine)
```
### SetLabelVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the visibility of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLabelVisibility(bool visible)
```
### SetMaplexLabelPlacementProperties(CIMMaplexLabelPlacementProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the maplex label placement properties definition of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMaplexLabelPlacementProperties(CIMMaplexLabelPlacementProperties properties)
```
### SetMaximumScale(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the maximum scale of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMaximumScale(double scale)
```
### SetMinimumScale(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the minimum scale of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMinimumScale(double scale)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the name of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetName(string name)
```
### SetPriority(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the priority of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPriority(int priority)
```
### SetStandardLabelPlacementProperties(CIMStandardLabelPlacementProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the standard label placement properties definition of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStandardLabelPlacementProperties(CIMStandardLabelPlacementProperties properties)
```
### SetTextSymbol(CIMTextSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the text symbol definition of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetTextSymbol(CIMTextSymbol textSymbol)
```
### SetUseCodedValue(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the use coded value of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseCodedValue(bool useCodedValue)
```
### SetWhereClause(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Sets the where clause of the label class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetWhereClause(string whereClause)
```
### UseCodedValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the use coded value of the label class.</p>


```csharp
public bool UseCodedValue { get; }
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the visibility of the label class.</p>


```csharp
public bool Visibility { get; }
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LabelClass.yml" sourcestartlinenumber="1">Gets the where clause of the label class.</p>


```csharp
public string WhereClause { get; }
```


