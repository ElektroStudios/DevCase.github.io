# GitHubUtil.IsUpdateAvailable Method 
 

Gets a value that determine whether exists a new version available of the specified reository on GitHub.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsUpdateAvailable(
	string userName,
	string repositoryName,
	Version currentVersion
)
```

**VB**<br />
``` VB
Public Shared Function IsUpdateAvailable ( 
	userName As String,
	repositoryName As String,
	currentVersion As Version
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim userName As String
Dim repositoryName As String
Dim currentVersion As Version
Dim returnValue As Boolean

returnValue = GitHubUtil.IsUpdateAvailable(userName, 
	repositoryName, currentVersion)
```

**C++**<br />
``` C++
public:
static bool IsUpdateAvailable(
	String^ userName, 
	String^ repositoryName, 
	Version^ currentVersion
)
```

**F#**<br />
``` F#
static member IsUpdateAvailable : 
        userName : string * 
        repositoryName : string * 
        currentVersion : Version -> bool 

```


#### Parameters
&nbsp;<dl><dt>userName</dt><dd>Type: System.String<br />The user name.</dd><dt>repositoryName</dt><dd>Type: System.String<br />The repository name.</dd><dt>currentVersion</dt><dd>Type: System.Version<br />The current version.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if exists a new version available on GitHub; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim user As String = "ElektroStudios"
Dim repo As String = "SmartBotKit"
Dim currentVersion As Version = Assembly.GetExecutingAssembly().GetName().Version

Dim isUpdateAvailable As Boolean = IsUpdateAvailable(user, repo, currentVersion)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GitHub_GitHubUtil">GitHubUtil Class</a><br /><a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />