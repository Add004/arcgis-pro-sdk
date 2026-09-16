# ArcadeProfile

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Arcade.html">Arcade</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The currently supported set of Arcade profiles that can be used.</p>


## Object Signature

```csharp
public enum ArcadeProfile
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The Arcade profile sets which functions are enabled in Arcade for
expression evaluation. Consult
<a href="https://developers.arcgis.com/arcade/profiles/">Profiles</a>.</p>


## Members

### Alias

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The alias profile allows the map author to write an expression to evaluate a feature or numeric value and return a text alias representing that value.</p>


```csharp
Alias = 0
```
### AttributeRuleCalculation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The attribute rule calculation profile is used by calculation attribute rules to update field values based on expression logic.</p>


```csharp
AttributeRuleCalculation = 1
```
### AttributeRuleConstraint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The attribute rule constraint profile is used by constraint attribute rules to evaluate whether or not a feature meets the criteria defined in the expression.</p>


```csharp
AttributeRuleConstraint = 2
```
### AttributeRuleValidation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The attribute rule validation profile is used by validation attribute rules to evaluate whether or not a feature meets the criteria defined in the expression.</p>


```csharp
AttributeRuleValidation = 3
```
### DictionaryRenderer

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The dictionary renderer profile allows the author of a dictionary renderer style to write an expression that evaluates to a text value used to construct a symbol.</p>


```csharp
DictionaryRenderer = 4
```
### FeatureDisplayTitle

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The feature display title profile allows the map author to write an expression that returns the preferred title to display for a feature (or row) in an application's user interface that uniquely represents the feature.</p>


```csharp
FeatureDisplayTitle = 17
```
### FeatureZ

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The feature Z profile is used to write an expression to calculate z values for features in a 3D scene.</p>


```csharp
FeatureZ = 5
```
### FieldCalculate

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The field calculate profile allows for expressions to update a field in field calculation tools.</p>


```csharp
FieldCalculate = 6
```
### FieldMapping

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The field mapping profile is used to write expressions to define a field map between source and target layers for transfer attribute workflows.</p>


```csharp
FieldMapping = 7
```
### GeoAnalytics

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The GeoAnalytics profile allows analysts to use expressions as input parameters to GeoAnalytics tools.</p>


```csharp
GeoAnalytics = 8
```
### Labeling

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The labeling profile allows the map author to write an expression that determines the label to show on the map for each feature.</p>


```csharp
Labeling = 9
```
### Layout

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The layout profile allows the map author to write an expression that evaluates to a value to be used in a layout dynamic text element or report.</p>


```csharp
Layout = 10
```
### MeasureVisualization

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The measure visualization profile allows the map author to write an expression that evaluates to a value used to drive the visualization of measure values along a line. This is used in the context of linear referencing hatching of m-aware lines.</p>


```csharp
MeasureVisualization = 11
```
### Popups

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">In the popup profile, map authors can write expressions that return values (i.e. attributes) for display in the view's popup. Expressions can be referenced in the popup content's text template, field tables, and media charts.</p>


```csharp
Popups = 12
```
### Restricted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The restricted profile for developer use where optional Arcade features are blocked. Prefer this as your default.</p>


```csharp
Restricted = 13
```
### Tasks

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">With the tasks profile, ArcGIS Pro Tasks authors can write verification actions to evaluate whether or not a selection of features meets the criteria defined in the expression.</p>


```csharp
Tasks = 14
```
### Unrestricted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The unrestricted profile for developer use where all optional Arcade features are allowed. Prefer Restricted if possible. Use with caution and only is an existing profile does not fit needs.</p>


```csharp
Unrestricted = 15
```
### Visualization

- Kind: field

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeProfile.yml" sourcestartlinenumber="1">The visualization profile allows the map author to write an expression that evaluates to a value used to drive the visualization. This could be used for a visual variable such as size, or as a value in a class breaks renderer.</p>


```csharp
Visualization = 16
```


