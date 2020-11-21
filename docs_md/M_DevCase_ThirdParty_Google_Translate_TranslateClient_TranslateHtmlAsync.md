# TranslateClient.TranslateHtmlAsync Method 
 

Asynchronously translates the specified text to the target language..

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> TranslateHtmlAsync(
	string html,
	GoogleLanguage from,
	GoogleLanguage to
)
```

**VB**<br />
``` VB
Public Function TranslateHtmlAsync ( 
	html As String,
	from As GoogleLanguage,
	to As GoogleLanguage
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TranslateClient
Dim html As String
Dim from As GoogleLanguage
Dim to As GoogleLanguage
Dim returnValue As Task(Of String)

returnValue = instance.TranslateHtmlAsync(html, 
	from, to)
```

**C++**<br />
``` C++
public:
Task<String^>^ TranslateHtmlAsync(
	String^ html, 
	GoogleLanguage from, 
	GoogleLanguage to
)
```

**F#**<br />
``` F#
member TranslateHtmlAsync : 
        html : string * 
        from : GoogleLanguage * 
        to : GoogleLanguage -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>html</dt><dd>Type: System.String<br />The Html to translate.</dd><dt>from</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />The source language.</dd><dt>to</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />\[Missing <param name="to"/> documentation for "M:DevCase.ThirdParty.Google.Translate.TranslateClient.TranslateHtmlAsync(System.String,DevCase.Core.NET.GoogleLanguage,DevCase.Core.NET.GoogleLanguage)"\]</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting Task(TResult) containing the translated Html.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New TranslateClient("YOUR API KEY")
Dim authSuccess As Boolean = Await client.AuthorizeAsync()
Dim sourceHtml As String =
    A Small Hello WorldHiThis is very minimal "Hello world" HTML document..Value
Dim translatedHtml As String =  Await client.TranslateHtmlAsync(sourceHtml, GoogleTranslateLanguage.EN, GoogleTranslateLanguage.ES)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Translate_TranslateClient">TranslateClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate Namespace</a><br />