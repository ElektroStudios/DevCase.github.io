# TranslateClient.TranslateTextAsync Method 
 

Asynchronously translates the specified text to the target language..

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> TranslateTextAsync(
	string text,
	GoogleLanguage from,
	GoogleLanguage to
)
```

**VB**<br />
``` VB
Public Function TranslateTextAsync ( 
	text As String,
	from As GoogleLanguage,
	to As GoogleLanguage
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TranslateClient
Dim text As String
Dim from As GoogleLanguage
Dim to As GoogleLanguage
Dim returnValue As Task(Of String)

returnValue = instance.TranslateTextAsync(text, 
	from, to)
```

**C++**<br />
``` C++
public:
Task<String^>^ TranslateTextAsync(
	String^ text, 
	GoogleLanguage from, 
	GoogleLanguage to
)
```

**F#**<br />
``` F#
member TranslateTextAsync : 
        text : string * 
        from : GoogleLanguage * 
        to : GoogleLanguage -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to translate.</dd><dt>from</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />The source language.</dd><dt>to</dt><dd>Type: <a href="T_DevCase_Core_NET_GoogleLanguage">DevCase.Core.NET.GoogleLanguage</a><br />\[Missing <param name="to"/> documentation for "M:DevCase.ThirdParty.Google.Translate.TranslateClient.TranslateTextAsync(System.String,DevCase.Core.NET.GoogleLanguage,DevCase.Core.NET.GoogleLanguage)"\]</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting Task(TResult) containing the translated text.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New TranslateClient("YOUR API KEY")
Dim authSuccess As Boolean = Await client.AuthorizeAsync()
Dim sourceText As String = "Hello World!"
Dim translatedText As String =  Await client.TranslateTextAsync(sourceText, GoogleTranslateLanguage.EN, GoogleTranslateLanguage.ES)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Translate_TranslateClient">TranslateClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate Namespace</a><br />