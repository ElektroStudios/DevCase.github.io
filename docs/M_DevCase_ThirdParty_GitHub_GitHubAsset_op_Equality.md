# GitHubAsset.Equality Operator 
 

Implements the operator =.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator ==(
	GitHubAsset asset1,
	GitHubAsset asset2
)
```

**VB**<br />
``` VB
Public Shared Operator = ( 
	asset1 As GitHubAsset,
	asset2 As GitHubAsset
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim asset1 As GitHubAsset
Dim asset2 As GitHubAsset
Dim returnValue As Boolean

returnValue = (asset1 = asset2)
```

**C++**<br />
``` C++
public:
static bool operator ==(
	GitHubAsset^ asset1, 
	GitHubAsset^ asset2
)
```

**F#**<br />
``` F#
static let inline (=)
        asset1 : GitHubAsset * 
        asset2 : GitHubAsset  : bool
```


#### Parameters
&nbsp;<dl><dt>asset1</dt><dd>Type: <a href="T_DevCase_ThirdParty_GitHub_GitHubAsset">DevCase.ThirdParty.GitHub.GitHubAsset</a><br />The first <a href="T_DevCase_ThirdParty_GitHub_GitHubAsset">GitHubAsset</a>.</dd><dt>asset2</dt><dd>Type: <a href="T_DevCase_ThirdParty_GitHub_GitHubAsset">DevCase.ThirdParty.GitHub.GitHubAsset</a><br />The second <a href="T_DevCase_ThirdParty_GitHub_GitHubAsset">GitHubAsset</a>.</dd></dl>

#### Return Value
Type: Boolean<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GitHub_GitHubAsset">GitHubAsset Class</a><br /><a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />