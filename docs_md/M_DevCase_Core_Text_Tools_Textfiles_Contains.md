# Textfiles.Contains Method 
 

Determines whether the source textfile contains the specified string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Contains(
	string sourceFilepath,
	string value,
	IEqualityComparer<string> comparer = null,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function Contains ( 
	sourceFilepath As String,
	value As String,
	Optional comparer As IEqualityComparer(Of String) = Nothing,
	Optional enc As Encoding = Nothing
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim value As String
Dim comparer As IEqualityComparer(Of String)
Dim enc As Encoding
Dim returnValue As Boolean

returnValue = Textfiles.Contains(sourceFilepath, 
	value, comparer, enc)
```

**C++**<br />
``` C++
public:
static bool Contains(
	String^ sourceFilepath, 
	String^ value, 
	IEqualityComparer<String^>^ comparer = nullptr, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Contains : 
        sourceFilepath : string * 
        value : string * 
        ?comparer : IEqualityComparer<string> * 
        ?enc : Encoding 
(* Defaults:
        let _comparer = defaultArg comparer null
        let _enc = defaultArg enc null
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>value</dt><dd>Type: System.String<br />\[Missing <param name="value"/> documentation for "M:DevCase.Core.Text.Tools.Textfiles.Contains(System.String,System.String,System.Collections.Generic.IEqualityComparer{System.String},System.Text.Encoding)"\]</dd><dt>comparer (Optional)</dt><dd>Type: System.Collections.Generic.IEqualityComparer(String)<br />\[Missing <param name="comparer"/> documentation for "M:DevCase.Core.Text.Tools.Textfiles.Contains(System.String,System.String,System.Collections.Generic.IEqualityComparer{System.String},System.Text.Encoding)"\]</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />\[Missing <param name="enc"/> documentation for "M:DevCase.Core.Text.Tools.Textfiles.Contains(System.String,System.String,System.Collections.Generic.IEqualityComparer{System.String},System.Text.Encoding)"\]</dd></dl>

#### Return Value
Type: Boolean<br />
**VB**<br />
``` VB
True
```
 if the value is found, otherwise, 
```
False
```
.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim contains As Boolean = Contains("C:\file.txt", "Hello World!", StringComparer.OrdinalIgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />