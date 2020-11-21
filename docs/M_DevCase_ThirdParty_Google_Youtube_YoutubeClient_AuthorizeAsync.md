# YoutubeClient.AuthorizeAsync Method 
 

Authorizes this instance to use Youtube API services.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<UserCredential> AuthorizeAsync()
```

**VB**<br />
``` VB
Public Function AuthorizeAsync As Task(Of UserCredential)
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeClient
Dim returnValue As Task(Of UserCredential)

returnValue = instance.AuthorizeAsync()
```

**C++**<br />
``` C++
public:
Task<UserCredential^>^ AuthorizeAsync()
```

**F#**<br />
``` F#
member AuthorizeAsync : unit -> Task<UserCredential> 

```


#### Return Value
Type: Task(UserCredential)<br />The resulting Task(TResult).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New YoutubeClient("C:\GoogleSecrets.json", "yourmail@gmail.com", YoutubeScopes.Youtube Or YoutubeScopes.ReadOnly)
Dim credential As UserCredential = Await client.AuthorizeAsync()
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_YoutubeClient">YoutubeClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube Namespace</a><br />