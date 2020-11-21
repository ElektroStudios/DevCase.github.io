# TranslateClient.Authorize Method 
 

Authorizes this instance to use Google Translate API service.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Authorize()
```

**VB**<br />
``` VB
Public Function Authorize As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As TranslateClient
Dim returnValue As Boolean

returnValue = instance.Authorize()
```

**C++**<br />
``` C++
public:
bool Authorize()
```

**F#**<br />
``` F#
member Authorize : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New TranslateClient("YOUR API KEY")
Dim authSuccess As Boolean = client.Authorize()
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Translate_TranslateClient">TranslateClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate Namespace</a><br />