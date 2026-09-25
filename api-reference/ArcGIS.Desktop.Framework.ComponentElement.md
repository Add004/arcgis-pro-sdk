# ComponentElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.ComponentElement.yml" sourcestartlinenumber="1">Represents a component registered in a category.</p>


## Object Signature

```csharp
public sealed class ComponentElement
```


## Members

### ContainerType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.ComponentElement.yml" sourcestartlinenumber="1">Gets the container type.</p>


```csharp
public string ContainerType { get; }
```
### CreateComponent(params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.ComponentElement.yml" sourcestartlinenumber="1">Instantiates the component.</p>


```csharp
public object CreateComponent(params object[] args)
```
### GetContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.ComponentElement.yml" sourcestartlinenumber="1">Returns the custom XML below the content node in DAML definition.</p>


```csharp
public XElement GetContent()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.ComponentElement.yml" sourcestartlinenumber="1">Gets the DAML identifier.</p>


```csharp
public string ID { get; }
```
### ReadAttribute(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.ComponentElement.yml" sourcestartlinenumber="1">Reads the string value of the specified attribute.</p>


```csharp
public string ReadAttribute(string name)
```


