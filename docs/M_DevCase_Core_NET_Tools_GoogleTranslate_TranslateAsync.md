# GoogleTranslate.TranslateAsync Method 
 

**Note: This API is now obsolete.**

Asynchronously use GoogleTranslate service to translate the specified text into another language.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)]
public static Task<string> TranslateAsync(
	string text,
	GoogleLanguage from,
	GoogleLanguage to
)
```

**VB**<br />
``` VB
<ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)>
Public Shared Function TranslateAsync ( 
	text As String,
	from As GoogleLanguage,
	to As GoogleLanguage
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim from As GoogleLanguage
Dim to As GoogleLanguage
Dim returnValue As Task(Of String)

returnValue = GoogleTranslate.TranslateAsync(text, 
	from, to)
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"Google free API is now limited to few searchs. Use the paid API instead.", 
	true)]
static Task<String^>^ TranslateAsync(
	String^ text, 
	GoogleLanguage from, 
	GoogleLanguage to
)
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)>]
static member TranslateAsync : 
        text : string * 
        from : GoogleLanguage * 
        to : GoogleLanguage -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The string to translate.</dd><dt>from</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />The source language.</dd><dt>to</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />The target language.</dd></dl>

#### Return Value
Type: Task(String)<br />The translated text.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>text</td></tr><tr><td>InvalidEnumArgumentException</td><td>from or to</td></tr><tr><td>HttpParseException</td><td>Unable to parse the Google's response.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim translatedText As String = Await TranslateAsync("Hello World!", GoogleLanguage.Auto, GoogleLanguage.ES)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_GoogleTranslate">GoogleTranslate Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />