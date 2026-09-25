# Gallery

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Represents an abstract base class for a gallery ribbon control.</p>


## Object Signature

```csharp
public abstract class Gallery : PlugIn, INotifyPropertyChanged
```

## Remarks

<p>
     A Gallery is a control that displays a collection of related items or Commands in the Ribbon. If there 
     are too many items in the gallery, an expand arrow is provided to display the rest of the collection in an expanded pane.  
     Galleries typically provide a richer representation of the choices offered, each often representing 
     a preview of the result if chosen.  Galleries can be organized to show multiple rows and columns 
     simultaneously and are excellent choices when you don’t want to be constrained by the smaller one 
     dimensional area offered by a menu. 
     </p>
<p>
     Galleries can present a condensed grid within the ribbon itself using the in-line gallery representation. 
     The items presented in this way are often either the most common or most recently used items depending on 
     the implementation.  The actual contents of a gallery are normally populated at runtime.  The Gallery 
     declaration below is populated entirely at runtime.  Relatively static aspects such as the caption, the 
     dropdown image, the tooltip, and the number of columns, are specified declaratively.
     </p>
<p>
     Gallery items are typically modeled through the <xref href="ArcGIS.Desktop.Framework.Contracts.GalleryItem" data-throw-if-not-resolved="false"></xref> class. GalleryItems have the following 
     properties: Icon, LargeIcon, Text, Group, and Tooltip. Custom GalleryItems can be created 
     through inheritance to encapsulate any additional properties and/or behavior as needed.
     </p>
<p>
     Gallery items are represented in the UI via an ItemTemplate. Galleries (and ComboBoxes) can specify a 
     custom template in their declaration. A simple default template is used for all galleries and combo boxes 
     that do not specify one. The default item template for galleries assumes a collection of GalleryItems; if you are using 
     your own item template, you can fill the collection with whatever type is appropriate. Note, when specifying a custom 
     template, you must list the file and its key. Also,  if you want grouping, make sure the objects
     expose a public Group property of type string as the binding logic uses this.
     </p>
<p>
     To better support a responsive UI experience, the framework provides a waiting spinner and 
     loading message on the gallery’s dropdown when it is trying to asynchronously load a large number 
     of items. The <xref href="ArcGIS.Desktop.Framework.Contracts.Gallery.LoadingMessage" data-throw-if-not-resolved="false"></xref> can be updated at runtime or set statically using the 
     loadingMessage attribute. Note, to get this default behavior, no heavy code should be put in the 
     gallery’s constructor since it will block the UI thread and prevent the spinner from showing up. The loading
     message only appears in drop down galleries (not in-inline).
     </p>
<p>
     All items added to the ItemCollection must be created on the main UI thread as these ultimately become the content 
     of buttons added to the gallery popup control.
     </p>
<p>
     Declaring Galleries in DAML:
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="44"> &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;            &lt;galleries&gt;
          &lt;gallery id=&quot;acme_BasemapGallery&quot; 
                 className=&quot;BasemapGallery&quot; 
                 caption=&quot;Basemap&quot; 
                 itemsInRow=&quot;3&quot; 
                 helpContextID=&quot;120000190&quot; 
                 itemWidth=&quot;140&quot; 
                 dataTemplateFile=&quot;pack://application:,,,/Acme;component/Styles/GalleryTemplates.xaml&quot;
                 templateID=&quot;BasemapItemTemplate&quot; 
                 showItemCaption=&quot;true&quot; 
                 resizable=&quot;true&quot; 
                 smallImage=&quot;pack://application:,,,/Acme;component/Images/Basemap16.png&quot;
                 largeImage=&quot;pack://application:,,,/Acme;component/Images/Basemap32.png&quot;&gt;
            &lt;tooltip&gt;Choose a basemap for your map.
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="59">The basemap is the reference data that displays under the notes and
other GIS data you have added to the map.
&lt;/tooltip&gt;
&lt;/gallery&gt;
&lt;/galleries&gt;</p>
<p>
Galleries can also be nested to produce a gallery of galleries. This is accomplished by adding a gallery element
within the gallery’s declaration.
</p>
<p>
<table><thead><tr><th class="term">DAML attributes</th></tr></thead><tbody><tr><td class="term">id</td><td class="description">Required identifier.</td></tr><tr><td class="term">caption</td><td class="description">The gallery heading.</td></tr><tr><td class="term">extendedCaption</td><td class="description">A more descriptive title.</td></tr><tr><td class="term">condition</td><td class="description">Automatically disable the button if the condition is not satisfied.</td></tr><tr><td class="term">loadOnClick</td><td class="description">Delay creating the actual control until it has been clicked. Default is true.</td></tr><tr><td class="term">disableIfBusy</td><td class="description">Automatically disable the button if the application is busy. Default true.</td></tr><tr><td class="term">loadingMessage</td><td class="description">Temporary message appearing while Pane is initializing.</td></tr><tr><td class="term">helpContextID</td><td class="description">The help topic to show.</td></tr><tr><td class="term">smallImage</td><td class="description">Image (16x16) used when button is small and middle size.</td></tr><tr><td class="term">largeImage</td><td class="description">Image (32x32) used when button is large size.</td></tr><tr><td class="term">overlaySmallImage</td><td class="description">Optional image overlay.</td></tr><tr><td class="term">overlayLargeImage</td><td class="description">Optional image overlay.</td></tr><tr><td class="term">dataTemplateFile</td><td class="description">The path to the file containing the custom item template.</td></tr><tr><td class="term">templateID</td><td class="description">The template ID in the dataTemplateFile.</td></tr><tr><td class="term">menuStyle</td><td class="description">Single column.</td></tr><tr><td class="term">resizable</td><td class="description">Controls whether the gallery's drop down window is expandable. Default is true.</td></tr><tr><td class="term">itemsInRow</td><td class="description">The number of items per row.</td></tr><tr><td class="term">itemWidth</td><td class="description">The width of the gallery items. Default is 32 pixels.</td></tr><tr><td class="term">dropDownHeight</td><td class="description">The height of drop down gallery.</td></tr><tr><td class="term">showGroup</td><td class="description">Specifies whether the items should be categorized according to their group. Default is false.</td></tr><tr><td class="term">showItemCaption</td><td class="description">Used with the default item template to hide or show the item's text below its image. Default is true.</td></tr><tr><td class="term">className</td><td class="description">Required class identifier. Optionally include namespace if not in default namespace.</td></tr><tr><td class="term">assembly</td><td class="description">Assembly name if not in the default assembly.</td></tr><tr><td class="term">publicKeyToken</td><td class="description">The necessary public key token if the assembly is strongly named.</td></tr><tr><td class="term">version</td><td class="description">The version of the dll if the assembly is strongly named.</td></tr></tbody></table>



## Members

### Add(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Adds an item to the collection.</p>


```csharp
protected void Add(object item)
```
### AlwaysFireOnClick

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets or sets the boolean to fire the click event even if the item is currently selected. The default value is false.</p>


```csharp
public bool AlwaysFireOnClick { get; set; }
```
### Clear()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Removes all the items from the internal collection.</p>


```csharp
protected void Clear()
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Clears the selection set.</p>


```csharp
public void ClearSelection()
```
### CloneItem(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">This is necessary for gallery customization dialog.<br>
It is used to create a new item when adding a new gallery item.</p>


```csharp
protected virtual object CloneItem(object sourceItem)
```
### CollectionView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">InRibbonGallery's bounded ItemSource. This collection filters out the items whose value of IGalleryItem.IsGroupVisible is false.</p>


```csharp
public ICollectionView CollectionView { get; }
```
### CopyFrom(ICollection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Add items from an existing collection.</p>


```csharp
protected void CopyFrom(ICollection collection)
```
### DefaultItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets or sets default gallery groups or items used to restore the dialog.
This is necessary for gallery customization dialog.</p>


```csharp
protected virtual object[] DefaultItems { get; set; }
```
### HasFailedToLoadItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets or sets the flag indicating the gallery has not initialized properly.</p>


```csharp
protected bool HasFailedToLoadItems { get; set; }
```
### Insert(int, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Inserts an element into the collection at the specified index.</p>


```csharp
protected void Insert(int index, object item)
```
### ItemCollection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets the gallery's items.</p>


```csharp
public ReadOnlyObservableCollection<object> ItemCollection { get; }
```
### ItemCollectionCopy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets a copy of the gallery's items which is safe to iterate over from any thead.</p>


```csharp
public List<object> ItemCollectionCopy { get; }
```
### ItemTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets or sets the custom item template.</p>


```csharp
public object ItemTemplate { get; protected set; }
```
### LoadingMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets or sets the message to show while items are loading into collection.</p>


```csharp
public string LoadingMessage { get; protected set; }
```
### Move(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Moves the item at the specified index to a new location in the collection.</p>


```csharp
protected void Move(int oldIndex, int newIndex)
```
### OnClick(GalleryItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Called when a <xref href="ArcGIS.Desktop.Framework.Contracts.GalleryItem" data-throw-if-not-resolved="false"></xref> is clicked.</p>


```csharp
protected virtual void OnClick(GalleryItem item)
```
### OnClick(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Called when a custom gallery item is clicked.</p>


```csharp
protected virtual void OnClick(object item)
```
### OnDropDownOpened()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Called when the gallery is expanded.</p>


```csharp
protected virtual void OnDropDownOpened()
```
### Remove(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Removes the first occurrence of a specific object from the collection.</p>


```csharp
protected bool Remove(object item)
```
### RemoveAt(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Removes the element at the specified index of the collection.</p>


```csharp
protected void RemoveAt(int index)
```
### SelectedIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets or sets the zero-based index of the selected item.</p>


```csharp
public int SelectedIndex { get; set; }
```
### SelectedItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Gets or sets the selected gallery item.</p>


```csharp
public object SelectedItem { get; set; }
```
### SetItemCollection(ObservableCollection&lt;object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Derived classes can push in an entire collection instead of adding items piecemeal.</p>


```csharp
protected void SetItemCollection(ObservableCollection<object> items)
```
### Uninitialize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Gallery.yml" sourcestartlinenumber="1">Called when the gallery is disposed to give the control an opportunity to clean up any resources.</p>


```csharp
protected virtual void Uninitialize()
```


