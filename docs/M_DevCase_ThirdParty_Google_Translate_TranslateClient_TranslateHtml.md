# TranslateClient.TranslateHtml Method 
 

Translates the specified Html to the target language.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string TranslateHtml(
	string html,
	GoogleLanguage from,
	GoogleLanguage to
)
```

**VB**<br />
``` VB
Public Function TranslateHtml ( 
	html As String,
	from As GoogleLanguage,
	to As GoogleLanguage
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As TranslateClient
Dim html As String
Dim from As GoogleLanguage
Dim to As GoogleLanguage
Dim returnValue As String

returnValue = instance.TranslateHtml(html, 
	from, to)
```

**C++**<br />
``` C++
public:
String^ TranslateHtml(
	String^ html, 
	GoogleLanguage from, 
	GoogleLanguage to
)
```

**F#**<br />
``` F#
member TranslateHtml : 
        html : string * 
        from : GoogleLanguage * 
        to : GoogleLanguage -> string 

```


#### Parameters
&nbsp;<dl><dt>html</dt><dd>Type: System.String<br />The Html to translate.</dd><dt>from</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />The source language.</dd><dt>to</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />\[Missing <param name="to"/> documentation for "M:DevCase.ThirdParty.Google.Translate.TranslateClient.TranslateHtml(System.String,DevCase.Core.NET.GoogleLanguage,DevCase.Core.NET.GoogleLanguage)"\]</dd></dl>

#### Return Value
Type: String<br />The resulting translated Html.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New TranslateClient("YOUR API KEY")
Dim authSuccess As Boolean = client.Authorize()
Dim sourceHtml As String =
    A Small Hello WorldHiThis is very minimal "Hello world" HTML document..Value
Dim translatedHtml As String =  client.TranslateHtml(sourceHtml, GoogleTranslateLanguage.EN, GoogleTranslateLanguage.ES)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Translate_TranslateClient">TranslateClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate Namespace</a><br />