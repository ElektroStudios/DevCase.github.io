# GoogleTranslate.Translate Method 
 

**Note: This API is now obsolete.**

Use GoogleTranslate service to translate the specified text into another language.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)]
public static string Translate(
	string text,
	GoogleLanguage from,
	GoogleLanguage to
)
```

**VB**<br />
``` VB
<ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)>
Public Shared Function Translate ( 
	text As String,
	from As GoogleLanguage,
	to As GoogleLanguage
) As String
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim from As GoogleLanguage
Dim to As GoogleLanguage
Dim returnValue As String

returnValue = GoogleTranslate.Translate(text, 
	from, to)
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"Google free API is now limited to few searchs. Use the paid API instead.", 
	true)]
static String^ Translate(
	String^ text, 
	GoogleLanguage from, 
	GoogleLanguage to
)
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)>]
static member Translate : 
        text : string * 
        from : GoogleLanguage * 
        to : GoogleLanguage -> string 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The string to translate.</dd><dt>from</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />The source language.</dd><dt>to</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />The target language.</dd></dl>

#### Return Value
Type: String<br />The resulting translated text.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>text</td></tr><tr><td>InvalidEnumArgumentException</td><td>from or to</td></tr><tr><td>HttpParseException</td><td>Unable to parse the Google's response.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim translatedText As String = Translate("Hello World!", GoogleLanguage.Auto, GoogleLanguage.Es)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_GoogleTranslate">GoogleTranslate Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />