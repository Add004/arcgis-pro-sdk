# State

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll


## Object Signature

```csharp
public sealed class State
```

## Remarks

<p>
     The framework incorporates a mechanism for triggering the activation of customizations based on 
     user defined conditions. Unlike classic events or callbacks, the binding between condition and 
     customizations is provided statically (declaratively) using DAML.  This mechanism provides a simplified 
     and declarative means for expressing when various GUI elements such as ribbon tabs, dock panes, 
     buttons and tools should and shouldn’t be visible or enabled within the application. Using 
     conditions also ensures that code modules and their associated resources are loaded and consumed 
     only when they are relevant, a feature that is critical to scalability, efficiency, and fast 
     application startup. The use of Conditions and State also simplifies coding by greatly reducing the 
     need for complex and largely redundant event wiring associated with more traditional models.
     </p>
<p>
     States are named Boolean values which symbolize a particular aspect of the application’s overall status; 
     for example, whether a particular view is active, or whether a particular type of feature is selected. 
     States are declared using ordinary character strings; to avoid name collisions, they are typically named 
     using the Plugin naming convention
     </p>
<p>
     Conditions are DAML expressions composed of one or more states, such as (A or B), where both A and B 
     are states. Conditions themselves are named so that they can be referenced by those DAML elements which 
     permit the use of conditions; for instance, a custom ribbon tab can be defined to show up on the ribbon 
     only when a map view is active, and hide when any other type of view is active
     </p>
<p>
     DECLARING STATES AND CONDITIONS:
     </p>
<p>
     States and Conditions are declared using DAML elements as follows:
     </p>
<p>
     A simple condition (consisting of only one state):
     </p>
<p>
  <pre><code class="lang-csharp">&lt;conditions&gt;
  &lt;insertCondition id="aSimpleCondition"&gt; 
   &lt;state id="someState"/&gt; 
  &lt;/insertCondition&gt;
&lt;/conditions&gt;</code></pre>

<p>
     A more complex condition:
     </p>
<p>
  <pre><code class="lang-csharp">&lt;conditions&gt;
  &lt;insertCondition id="aMoreComplexCondition"&gt; 
    &lt;and&gt;
      &lt;state id="someState"/&gt; 
      &lt;or/&gt;
        &lt;state id="someOtherState"/&gt;
        &lt;state id="yetAnotherState"/&gt;
      &lt;/or/&gt;
    &lt;and&gt;
  &lt;/insertCondition&gt;
&lt;/conditions&gt;</code></pre>

<p>
     The above condition evaluates to (someState AND (someOtherState OR yetAnotherState)). 
     </p>
<p>
     Conditions are defined at the root level in the DAML file—outside the scope of any extension block—since 
     they are simply expressions (without an active aspect), and do not need to be associated with any 
     controlling extension; conditions should be considered global in scope.  The Boolean operators And, Or, 
     and Not can be combined recursively to form complex conditional expressions if necessary, but conditions 
     themselves cannot be used (recursively) in place of  states within another Condition block.  
     </p>
<p>
     Conditions are associated with a particular Plugin using the Condition attribute:
     </p>
<p>
     For example, the specified custom dockpane appears only when the active view is a map view.
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="72"> &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;&lt;dockpane id=&quot;myDockPane&quot; condition=&quot;esri_mapping_MapView&quot; &gt;&lt;/code&gt;&lt;/pre&gt;&lt;/p&gt;
    &lt;p&gt;
         STATE ACTIVATION
         &lt;/p&gt;
    &lt;p&gt;
         The framework defines a fixed set of activation behaviors which can be triggered using conditions. States are 
         maintained in state tables, where state is said to be activated if the state exists in the table, and 
         deactivated otherwise. While the application runs, the state tables within the framework are periodically 
         monitored for changes. When a change is detected, the tables are matched against any conditions currently 
         defined, and the appropriate activation (or deactivation) is triggered in response.
         &lt;/p&gt;
    &lt;p&gt;
      &lt;table&gt;&lt;thead&gt;&lt;tr&gt;&lt;th class=&quot;term&quot;&gt;Plugin Type&lt;/th&gt;&lt;th class=&quot;term&quot;&gt;Framework Provided Activation&lt;/th&gt;&lt;/tr&gt;&lt;/thead&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td class=&quot;term&quot;&gt;Ribbon Tab&lt;/td&gt;&lt;td class=&quot;description&quot;&gt;
         Tab is shown or hidden based on the associated condition.  When the Tab first appears, other 
         objects which appear on the tab may load if they are visible.&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td class=&quot;term&quot;&gt;DockPane&lt;/td&gt;&lt;td class=&quot;description&quot;&gt;
         DockPanes can initially be shown based on the associated condition. The DockPane object itself will 
         not be loaded or created until the condition is initially met. DockPanes are not automatically
         hidden when their condition no longer matches.&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td class=&quot;term&quot;&gt;Controls (Buttons, Tools, Etc.)&lt;/td&gt;&lt;td class=&quot;description&quot;&gt;
         Control Plugins are enabled and disabled based on their associated condition. The Control Plugin object 
         itself will not be loaded or created until the condition is initially met, and thereafter, OnUpdate will 
         not be called unless the supplied context is currently satisfied.  Note that the loadOnClick attribute 
         is checked after the Condition, so loadOnClick controls will still appear disabled if their Condition 
         hasn’t yet been satisfied..&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td class=&quot;term&quot;&gt;Property Page&lt;/td&gt;&lt;td class=&quot;description&quot;&gt;
         A property sheet contains a collection of property pages. The sheet will not show pages that specify a 
         condition that is not met.&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt;
    &lt;/p&gt;
    &lt;p&gt;
         IMPLICIT AND EXPLICIT STATE
         &lt;/p&gt;
    &lt;p&gt;
         States can be either implicit or explicit. Implicit states are those which are intrinsically defined and 
         controlled by the framework itself; these states are activated and deactivated automatically. 
         &lt;/p&gt;
    &lt;p&gt;
         The framework currently defines the following implicit states:

         &lt;table&gt;&lt;thead&gt;&lt;tr&gt;&lt;th class=&quot;term&quot;&gt;Implicit State&lt;/th&gt;&lt;th class=&quot;term&quot;&gt;Details&lt;/th&gt;&lt;/tr&gt;&lt;/thead&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td class=&quot;term&quot;&gt;Active Pane&lt;/td&gt;&lt;td class=&quot;description&quot;&gt;
         The ID of the active Pane is designated as an implicit state and activated when the pane is active.
         &lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td class=&quot;term&quot;&gt;Active Tab&lt;/td&gt;&lt;td class=&quot;description&quot;&gt;
         The ID of the active Tab is designated as an implicit state and activated when the tab is active.
         &lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td class=&quot;term&quot;&gt;Active Tool&lt;/td&gt;&lt;td class=&quot;description&quot;&gt;
         The ID of the active Tool is designated as an implicit state and activated when the tool is active.
         &lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td class=&quot;term&quot;&gt;Module Loaded&lt;/td&gt;&lt;td class=&quot;description&quot;&gt;
         When a module is loaded, its ID is designated as an implicit state and activated. When unloaded, its ID is deactivated.
         &lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt;&lt;/p&gt;
    &lt;p&gt;
         Explicit states are set manually using developer supplied code; the meanings of these states are usually 
         defined by the developer and used to identify more specific types of context such as custom modes; i.e.: &quot;I’m editing&quot;, 
         or a custom status: &quot;a raster layer is selected in the TOC.&quot;
         &lt;/p&gt;
    &lt;p&gt;
         Explicit state changes are made by calling Activate or Deactivate on the State object.

         &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;// Called when a raster layer is selected.
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="126">State.Activate(&quot;esri_core_RasterLayerSelected&quot;);</p>
<p sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="128">// Called when editing mode is exited.
State.Deactivate(&quot;esri_core_EditingModeExited&quot;);</p>
<p>
LOCALITY OF STATE
</p>
<p>
State tables are maintained at two levels within the framework: Application level state, and Pane level state.
Applications built with the framework are primarily pane centric applications, and as such the framework is
designed to support several independent activities, each potentially associated with different pane instances.
Each pane may have state which is relevant only to that instance and should not be altered if the user simply
switches to another pane; e.g. the current selection or current tool. For this reason, each pane instance
maintains its own state table accessible via the Pane class:</p>
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="141">         &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;// Deactivate a state associated with a particular view.
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="142">Pane.State.Deactivate(&quot;esri_mapping_FeatureSelected&quot;);</p>
<p>
Application level state contains global state relevant to the application as a whole such as which view is
currently active, or whether a particular extension is currently loaded. Application level state is accessed
via the Application class:</p>
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="148">         &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;// Activate a state associated the application as a whole.
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="149">Application.State.Activate(&quot;esri_mapping_DigitizerEnabled&quot;);</p>
<p>
During condition matching, the framework will always consider the state associated with application level,
as well as the state associated with the currently active pane; thus a condition will be satisfied if its
expression evaluates positively on the combination of these two tables.  It is important to activate or
deactivate state at the appropriate level (depending on the type of state).
</p>


## Members

### Activate(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="1">Adds the specified state to the state set.</p>


```csharp
public void Activate(string stateID)
```
### Contains(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="1">Returns whether the specified state is turned on in the state set.</p>


```csharp
public bool Contains(string stateID)
```
### Deactivate(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="1">Removes the specified state from the state set.</p>


```csharp
public void Deactivate(string stateID)
```
### NoState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.State.yml" sourcestartlinenumber="1">Gets a boolean indicating true if state set is empty.</p>


```csharp
public bool NoState { get; }
```


