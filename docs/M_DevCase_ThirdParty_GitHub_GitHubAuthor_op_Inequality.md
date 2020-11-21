# GitHubAuthor.Inequality Operator 
 

Implements the operator <>.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator !=(
	GitHubAuthor author1,
	GitHubAuthor author2
)
```

**VB**<br />
``` VB
Public Shared Operator <> ( 
	author1 As GitHubAuthor,
	author2 As GitHubAuthor
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim author1 As GitHubAuthor
Dim author2 As GitHubAuthor
Dim returnValue As Boolean

returnValue = (author1 <> author2)
```

**C++**<br />
``` C++
public:
static bool operator !=(
	GitHubAuthor^ author1, 
	GitHubAuthor^ author2
)
```

**F#**<br />
``` F#
static let inline (<>)
        author1 : GitHubAuthor * 
        author2 : GitHubAuthor  : bool
```


#### Parameters
&nbsp;<dl><dt>author1</dt><dd>Type: <a href="T_DevCase_ThirdParty_GitHub_GitHubAuthor">DevCase.ThirdParty.GitHub.GitHubAuthor</a><br />The first <a href="T_DevCase_ThirdParty_GitHub_GitHubAuthor">GitHubAuthor</a>.</dd><dt>author2</dt><dd>Type: <a href="T_DevCase_ThirdParty_GitHub_GitHubAuthor">DevCase.ThirdParty.GitHub.GitHubAuthor</a><br />The second <a href="T_DevCase_ThirdParty_GitHub_GitHubAuthor">GitHubAuthor</a>.</dd></dl>

#### Return Value
Type: Boolean<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GitHub_GitHubAuthor">GitHubAuthor Class</a><br /><a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />