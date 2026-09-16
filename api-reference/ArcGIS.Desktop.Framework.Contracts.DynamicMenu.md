# DynamicMenu

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Represents a menu that is populated at run-time. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class DynamicMenu : PlugIn, INotifyPropertyChanged
```

## Remarks

<p>
     Unlike declaratively defined menus, dynamic menus are populated at run-time. Derived classes must add items in their
     <xref href="ArcGIS.Desktop.Framework.Contracts.DynamicMenu.OnPopup" data-throw-if-not-resolved="false"></xref> override which is invoked before the menu opens. Dynamic menus may contain simple items consisting of a caption
     and image, or references to existing DAML controls including other dynamic menus. The <xref href="ArcGIS.Desktop.Framework.Contracts.DynamicMenu.OnClick(System.Int32)" data-throw-if-not-resolved="false"></xref> override
     is invoked with the specified index when an item is clicked. All menu items are cleared after the popup closes.
     </p>
<p>
     Dynamic menus can reside directly on the ribbon or on other menus. If the dynamic menu is on a menu and 
     the inline attribute is set to true, the items will be added directly onto the hosting menu instead of 
     being added to a pull-right submenu.
     </p>
<p>
      Declaring Dynamic menus in DAML:
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="15"> &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;&lt;dynamicMenu caption=&quot;Acme Menu &quot; 
         className=&quot;DynoMenu&quot; 
         id=&quot;acme_dynoMenu&quot; 
         largeImage=&quot;pack://application:,,,/ProTestApp;component/Images/MenuImage32.png&quot; 
         smallImage=&quot;pack://application:,,,/ProTestApp;component/Images/MenuImage16.png&quot; &gt;
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="20">&lt;tooltip heading=&quot;Heading&quot; image=&quot;pack://application:,,,/Acme;component/Images/MenuImage16.png&quot;&gt;Some text&lt;/tooltip&gt;
&lt;/dynamicMenu&gt;</p>
<p>
<table><thead><tr><th class="term">DAML attributes</th></tr></thead><tbody><tr><td class="term">assembly</td><td class="description">Assembly name if not in the default assembly.</td></tr><tr><td class="term">caption</td><td class="description">The heading.</td></tr><tr><td class="term">categoryRefID</td><td class="description">Adds control to a specific component category.</td></tr><tr><td class="term">className</td><td class="description">Required class identifier. Optionally include namespace if not in default namespace.</td></tr><tr><td class="term">condition</td><td class="description">Automatically disable the button if the condition is not satisfied.</td></tr><tr><td class="term">disableIfBusy</td><td class="description">Automatically disable the button if the application is busy. Default true.</td></tr><tr><td class="term">extendedCaption</td><td class="description">A more descriptive title.</td></tr><tr><td class="term">id</td><td class="description">Required identifier.</td></tr><tr><td class="term">largeImage</td><td class="description">Image (32x32) used when button is large size.</td></tr><tr><td class="term">publicKeyToken</td><td class="description">The necessary public key token if the assembly is strongly named.</td></tr><tr><td class="term">smallImage</td><td class="description">Image (16x16) used when button is small and middle size.</td></tr><tr><td class="term">version</td><td class="description">The version of the dll if the assembly is strongly named.</td></tr></tbody></table>



## Members

### DynamicMenu()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Represents a menu that is populated at run-time. This is an abstract class.</p>


```csharp
protected DynamicMenu()
```
### Add(DynamicMenu, Func&lt;object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Adds a dynamic menu at runtime to the menu with an option to update the control's caption.</p>


```csharp
protected void Add(DynamicMenu menu, Func<object> menuContext = null)
```
### Add(string, string, bool, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Adds a new item to the menu that points to a delegate.</p>


```csharp
protected void Add(string caption, string imagePath = "", bool isChecked = false, bool isEnabled = true, bool isBold = false)
```
### Add(string, string, bool, bool, bool, Delegate, params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Adds a new item to the menu that points to a delegate.</p>


```csharp
protected void Add(string caption, string imagePath = "", bool isChecked = false, bool isEnabled = true, bool isBold = false, Delegate method = null, params object[] args)
```
### Add(string, string, string, string, ImageSource, bool, bool, bool, Delegate, params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Adds a new item to the menu that points to a delegate.</p>


```csharp
protected void Add(string caption, string imagePath = "", string tooltipTitle = "", string tooltipText = "", ImageSource tooltipImage = null, bool isChecked = false, bool isEnabled = true, bool isBold = false, Delegate method = null, params object[] args)
```
### AddReference(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Adds an existing DAML control to the menu.</p>


```csharp
protected void AddReference(string refID)
```
### AddReference(string, string, Func&lt;object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Adds an existing DAML control to the menu with an option to update the control's caption.</p>


```csharp
protected void AddReference(string refID, string newCaption = "", Func<object> menuContext = null)
```
### AddSeparator()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Adds a separator between the menu items.</p>


```csharp
protected void AddSeparator()
```
### ContextItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Gets and sets the contextItem.</p>


```csharp
protected object ContextItem { get; set; }
```
### OnClick(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Invoked when a menu item is clicked.</p>


```csharp
protected virtual void OnClick(int index)
```
### OnPopup()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DynamicMenu.yml" sourcestartlinenumber="1">Invoked when the menu is opened.</p>


```csharp
protected virtual void OnPopup()
```


