# NddeUtil.GetFirefoxUrl Method 
 

Gets the url of the active tab-page from a running Firefox process.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ndde">DevCase.ThirdParty.Ndde</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetFirefoxUrl()
```

**VB**<br />
``` VB
Public Shared Function GetFirefoxUrl As String
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As String

returnValue = NddeUtil.GetFirefoxUrl()
```

**C++**<br />
``` C++
public:
static String^ GetFirefoxUrl()
```

**F#**<br />
``` F#
static member GetFirefoxUrl : unit -> string 

```


#### Return Value
Type: String<br />The url of the active tab-page from a running Firefox process.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim url As String = GetFirefoxUrl()
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ndde_NddeUtil">NddeUtil Class</a><br /><a href="N_DevCase_ThirdParty_Ndde">DevCase.ThirdParty.Ndde Namespace</a><br />