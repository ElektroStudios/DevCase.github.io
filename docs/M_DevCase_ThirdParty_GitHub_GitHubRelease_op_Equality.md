# GitHubRelease.Equality Operator 
 

Implements the operator =.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator ==(
	GitHubRelease release1,
	GitHubRelease release2
)
```

**VB**<br />
``` VB
Public Shared Operator = ( 
	release1 As GitHubRelease,
	release2 As GitHubRelease
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim release1 As GitHubRelease
Dim release2 As GitHubRelease
Dim returnValue As Boolean

returnValue = (release1 = release2)
```

**C++**<br />
``` C++
public:
static bool operator ==(
	GitHubRelease^ release1, 
	GitHubRelease^ release2
)
```

**F#**<br />
``` F#
static let inline (=)
        release1 : GitHubRelease * 
        release2 : GitHubRelease  : bool
```


#### Parameters
&nbsp;<dl><dt>release1</dt><dd>Type: <a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">DevCase.ThirdParty.GitHub.GitHubRelease</a><br />The first <a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease</a>.</dd><dt>release2</dt><dd>Type: <a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">DevCase.ThirdParty.GitHub.GitHubRelease</a><br />The second <a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease</a>.</dd></dl>

#### Return Value
Type: Boolean<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease Class</a><br /><a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />