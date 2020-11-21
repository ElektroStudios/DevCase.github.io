# GitHubUtil.GetLatestRelease Method 
 

Gets the latest release from the specified repository on GitHub.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static GitHubRelease GetLatestRelease(
	string userName,
	string repositoryName
)
```

**VB**<br />
``` VB
Public Shared Function GetLatestRelease ( 
	userName As String,
	repositoryName As String
) As GitHubRelease
```

**VB Usage**<br />
``` VB Usage
Dim userName As String
Dim repositoryName As String
Dim returnValue As GitHubRelease

returnValue = GitHubUtil.GetLatestRelease(userName, 
	repositoryName)
```

**C++**<br />
``` C++
public:
static GitHubRelease^ GetLatestRelease(
	String^ userName, 
	String^ repositoryName
)
```

**F#**<br />
``` F#
static member GetLatestRelease : 
        userName : string * 
        repositoryName : string -> GitHubRelease 

```


#### Parameters
&nbsp;<dl><dt>userName</dt><dd>Type: System.String<br />The user name.</dd><dt>repositoryName</dt><dd>Type: System.String<br />The repository name.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease</a><br />The resulting <a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim release As GitHubRelease = GetLatestRelease("ElektroStudios", "SmartBotKit")
Console.WriteLine("RELEASE: {0}", release.ToString())
Console.WriteLine()

Console.WriteLine("BODY:")
Console.WriteLine(release.Body)
Console.WriteLine()

For Each asset As GitHubAsset In release.Assets
    Console.WriteLine("ASSET: {0}", asset.ToString())
Next asset
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GitHub_GitHubUtil">GitHubUtil Class</a><br /><a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />