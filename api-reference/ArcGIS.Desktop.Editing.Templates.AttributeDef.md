# AttributeDef

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Templates.html">Templates</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Defines each of the parameter value <xref href="ArcGIS.Desktop.Editing.Templates.BuilderMethod.Options?text=Options" data-throw-if-not-resolved="false"></xref> that are required for a particular <xref href="ArcGIS.Desktop.Editing.Templates.BuilderMethod?text=BuilderMethod" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AttributeDef
```


## Members

### AttributeDef(string, string, FieldType, object, bool, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Creates an AttributeDef</p>


```csharp
public AttributeDef(string id, string name, FieldType type, object defaultValue, bool isNullable, bool unitAsMeters = false)
```
### AttributeDef(string, string, double, bool, double, double, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Creates an AttributeDef</p>


```csharp
public AttributeDef(string id, string name, double defaultValue, bool isNullable, double minValue, double maxValue, bool unitAsMeters = false)
```
### AttributeDef(string, string, string, bool, IEnumerable&lt;string&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Creates an AttributeDef</p>


```csharp
public AttributeDef(string id, string name, string defaultValue, bool isNullable, IEnumerable<string> allowedValues)
```
### DefaultValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Gets the default value of this AttributeDef.</p>


```csharp
public object DefaultValue { get; }
```
### Domain

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Gets the domain of this AttributeDef.</p>


```csharp
public Domain Domain { get; }
```
### FieldType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Gets the field type of this AttributeDef.</p>


```csharp
public FieldType FieldType { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Gets the unique identifier for this AttributeDef.</p>


```csharp
public string ID { get; }
```
### IsNullable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Gets whether this AttributeDef allows a null value.</p>


```csharp
public bool IsNullable { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Gets the name of this AttributeDef.</p>


```csharp
public string Name { get; }
```
### UnitAsMeters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.AttributeDef.yml" sourcestartlinenumber="1">Gets whether this AttributeDef requires units as meters.</p>


```csharp
public bool UnitAsMeters { get; }
```


