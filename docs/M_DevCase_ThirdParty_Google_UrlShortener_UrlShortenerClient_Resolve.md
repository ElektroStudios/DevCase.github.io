# UrlShortenerClient.Resolve Method (String)
 

Resolves a shortened Url.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Resolve(
	string url
)
```

**VB**<br />
``` VB
Public Function Resolve ( 
	url As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As UrlShortenerClient
Dim url As String
Dim returnValue As String

returnValue = instance.Resolve(url)
```

**C++**<br />
``` C++
public:
String^ Resolve(
	String^ url
)
```

**F#**<br />
``` F#
member Resolve : 
        url : string -> string 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The shortened Url to resolve.</dd></dl>

#### Return Value
Type: String<br />The resulting resolved Url.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New UrlShortenerClient("YOUR API KEY")
Dim authSuccess As Boolean = client.Authorize()
Dim shortenedUrl As String = "http://goo.gl/Pfn8S"
Dim resolvedUrl As String = client.Resolve(shortenedUrl)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient">UrlShortenerClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_Resolve">Resolve Overload</a><br /><a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener Namespace</a><br />