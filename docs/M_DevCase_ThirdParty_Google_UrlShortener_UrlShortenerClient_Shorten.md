# UrlShortenerClient.Shorten Method (String)
 

Shortens the specified Url.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Shorten(
	string url
)
```

**VB**<br />
``` VB
Public Function Shorten ( 
	url As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As UrlShortenerClient
Dim url As String
Dim returnValue As String

returnValue = instance.Shorten(url)
```

**C++**<br />
``` C++
public:
String^ Shorten(
	String^ url
)
```

**F#**<br />
``` F#
member Shorten : 
        url : string -> string 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The source Url to shorten.</dd></dl>

#### Return Value
Type: String<br />The resulting shortened Url.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New UrlShortenerClient("YOUR API KEY")
Dim authSuccess As Boolean = client.Authorize()
Dim sourceUrl As String = "https://msdn.microsoft.com/"
Dim shortenedUrl As String =  client.Shorten(sourceUrl)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient">UrlShortenerClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_Shorten">Shorten Overload</a><br /><a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener Namespace</a><br />