# UrlShortenerClient.ResolveAsync Method (String)
 

Asynchronously resolves a shortened Url.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> ResolveAsync(
	string url
)
```

**VB**<br />
``` VB
Public Function ResolveAsync ( 
	url As String
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As UrlShortenerClient
Dim url As String
Dim returnValue As Task(Of String)

returnValue = instance.ResolveAsync(url)
```

**C++**<br />
``` C++
public:
Task<String^>^ ResolveAsync(
	String^ url
)
```

**F#**<br />
``` F#
member ResolveAsync : 
        url : string -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The shortened Url to resolve.</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting Task(TResult) containing the resolved Url.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New UrlShortenerClient("YOUR API KEY")
Dim authSuccess As Boolean = Await client.AuthorizeAsync()
Dim shortenedUrl As String = "http://goo.gl/Pfn8S"
Dim resolvedUrl As String = Await client.ResolveAsync(shortenedUrl)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient">UrlShortenerClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_ResolveAsync">ResolveAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener Namespace</a><br />