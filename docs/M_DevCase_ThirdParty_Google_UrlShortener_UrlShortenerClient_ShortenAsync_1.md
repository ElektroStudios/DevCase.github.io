# UrlShortenerClient.ShortenAsync Method (Uri)
 

Asynchronously shortens the specified Url.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> ShortenAsync(
	Uri uri
)
```

**VB**<br />
``` VB
Public Function ShortenAsync ( 
	uri As Uri
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As UrlShortenerClient
Dim uri As Uri
Dim returnValue As Task(Of String)

returnValue = instance.ShortenAsync(uri)
```

**C++**<br />
``` C++
public:
Task<String^>^ ShortenAsync(
	Uri^ uri
)
```

**F#**<br />
``` F#
member ShortenAsync : 
        uri : Uri -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The source URI to shorten.</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting Task(TResult) containing the shortened Url.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New UrlShortenerClient("YOUR API KEY")
Dim authSuccess As Boolean = Await client.AuthorizeAsync()
Dim sourceUrl As String = "https://msdn.microsoft.com/"
Dim shortenedUrl As String = Await client.ShortenAsync(sourceUrl)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient">UrlShortenerClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_ShortenAsync">ShortenAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener Namespace</a><br />