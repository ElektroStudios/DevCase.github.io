# UrlShortenerClient.AuthorizeAsync Method 
 

Asynchronously authorizes this instance to use UrlShortener API service.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<bool> AuthorizeAsync()
```

**VB**<br />
``` VB
Public Function AuthorizeAsync As Task(Of Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim instance As UrlShortenerClient
Dim returnValue As Task(Of Boolean)

returnValue = instance.AuthorizeAsync()
```

**C++**<br />
``` C++
public:
Task<bool>^ AuthorizeAsync()
```

**F#**<br />
``` F#
member AuthorizeAsync : unit -> Task<bool> 

```


#### Return Value
Type: Task(Boolean)<br />`true` (`True` in Visual Basic) if the operation succeeds, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New UrlShortenerClient("YOUR API KEY")
Dim authSuccess As Boolean = Await client.AuthorizeAsync()
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient">UrlShortenerClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener Namespace</a><br />