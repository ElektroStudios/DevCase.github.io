# JsonUtil.BeautifyJson Method 
 

Beautifies the contents of a unbeautified JSON string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string BeautifyJson(
	string json,
	string indentString = ""
)
```

**VB**<br />
``` VB
Public Shared Function BeautifyJson ( 
	json As String,
	Optional indentString As String = ""
) As String
```

**VB Usage**<br />
``` VB Usage
Dim json As String
Dim indentString As String
Dim returnValue As String

returnValue = JsonUtil.BeautifyJson(json, 
	indentString)
```

**C++**<br />
``` C++
public:
static String^ BeautifyJson(
	String^ json, 
	String^ indentString = L""
)
```

**F#**<br />
``` F#
static member BeautifyJson : 
        json : string * 
        ?indentString : string 
(* Defaults:
        let _indentString = defaultArg indentString ""
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>json</dt><dd>Type: System.String<br />The source (unbeautified) JSON string.</dd><dt>indentString (Optional)</dt><dd>Type: System.String<br />The string used to write the indentation blank space. 

 By default the tabulation char is used, you can change this value to " " (four white spaces) or whatever.</dd></dl>

#### Return Value
Type: String<br />The resulting beautified JSON string.

## Remarks
All credits goes to @Peter Long: <a href="http://stackoverflow.com/a/6237866/1248295" target="_blank">http://stackoverflow.com/a/6237866/1248295</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim json As String = <a>{"colorsArray":[{"colorName":"red","hexValue":"#f00"},{"colorName":"green","hexValue":"#0f0"}]}</a>.Value
Dim beautified As String = BeautifyJson(json)

MessageBox.Show(beautified)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Xml_Tools_JsonUtil">JsonUtil Class</a><br /><a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools Namespace</a><br />