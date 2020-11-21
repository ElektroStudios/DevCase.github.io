# GitHubUtil.GetRelease Method 
 

Gets a release that matches the specified version from the specified repository on GitHub.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static GitHubRelease GetRelease(
	string userName,
	string repositoryName,
	Version version
)
```

**VB**<br />
``` VB
Public Shared Function GetRelease ( 
	userName As String,
	repositoryName As String,
	version As Version
) As GitHubRelease
```

**VB Usage**<br />
``` VB Usage
Dim userName As String
Dim repositoryName As String
Dim version As Version
Dim returnValue As GitHubRelease

returnValue = GitHubUtil.GetRelease(userName, 
	repositoryName, version)
```

**C++**<br />
``` C++
public:
static GitHubRelease^ GetRelease(
	String^ userName, 
	String^ repositoryName, 
	Version^ version
)
```

**F#**<br />
``` F#
static member GetRelease : 
        userName : string * 
        repositoryName : string * 
        version : Version -> GitHubRelease 

```


#### Parameters
&nbsp;<dl><dt>userName</dt><dd>Type: System.String<br />The user name.</dd><dt>repositoryName</dt><dd>Type: System.String<br />The repository name.</dd><dt>version</dt><dd>Type: System.Version<br />The version of the release.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease</a><br />The resulting <a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim release As GitHubRelease = GetRelease("ElektroStudios", "SmartBotKit", New Version("1.3"))
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