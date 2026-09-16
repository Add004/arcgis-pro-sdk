# SpellChecker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Utilities.html">Utilities</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.SpellChecker.yml" sourcestartlinenumber="1">Spell checking object</p>


## Object Signature

```csharp
public class SpellChecker
```


## Members

### SpellChecker(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.SpellChecker.yml" sourcestartlinenumber="1">Creates a SpellChecker object using the specified language ID.</p>


```csharp
public SpellChecker(string lang)
```
### AddToDictionary(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.SpellChecker.yml" sourcestartlinenumber="1">Adds the specified word to the dictionary.</p>


```csharp
public void AddToDictionary(string word)
```
### CheckSentence(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.SpellChecker.yml" sourcestartlinenumber="1">Returns a list of tuples of integers, each containing the start position and length of each spelling error in the sentence.</p>


```csharp
public List<Tuple<int, int>> CheckSentence(string sentence)
```
### CustomDictionaries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.SpellChecker.yml" sourcestartlinenumber="1">Return the list of custom dictionaries.</p>


```csharp
public IList CustomDictionaries { get; }
```
### GetSuggestions(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.SpellChecker.yml" sourcestartlinenumber="1">Returns an array of suggestions for the specified word.  Returns null if the word is properly spelled.</p>


```csharp
public string[] GetSuggestions(string word)
```
### IgnoreAll(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.SpellChecker.yml" sourcestartlinenumber="1">Will ignore the specified spelling error for the lifetime of the spell checker object.</p>


```csharp
public void IgnoreAll(string word)
```
### Language

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.SpellChecker.yml" sourcestartlinenumber="1">Gets or Sets the Spellchecker language per RFC 3066. For example, use en-US for U.S. English or fr-FR for France French.</p>


```csharp
public string Language { get; set; }
```


