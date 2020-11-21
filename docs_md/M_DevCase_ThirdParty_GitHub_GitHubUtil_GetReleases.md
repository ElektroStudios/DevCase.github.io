# GitHubUtil.GetReleases Method 
 

Gets the releases from the specified repository on GitHub.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<GitHubRelease> GetReleases(
	string userName,
	string repositoryName
)
```

**VB**<br />
``` VB
Public Shared Function GetReleases ( 
	userName As String,
	repositoryName As String
) As ReadOnlyCollection(Of GitHubRelease)
```

**VB Usage**<br />
``` VB Usage
Dim userName As String
Dim repositoryName As String
Dim returnValue As ReadOnlyCollection(Of GitHubRelease)

returnValue = GitHubUtil.GetReleases(userName, 
	repositoryName)
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<GitHubRelease^>^ GetReleases(
	String^ userName, 
	String^ repositoryName
)
```

**F#**<br />
``` F#
static member GetReleases : 
        userName : string * 
        repositoryName : string -> ReadOnlyCollection<GitHubRelease> 

```


#### Parameters
&nbsp;<dl><dt>userName</dt><dd>Type: System.String<br />The user name.</dd><dt>repositoryName</dt><dd>Type: System.String<br />The repository name.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(<a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease</a>)<br />A ReadOnlyCollection(T) collection containing the releases.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim releases As ReadOnlyCollection(Of GitHubRelease) = GetReleases("ElektroStudios", "SmartBotKit")

For Each release As GitHubRelease In releases
    Console.WriteLine("RELEASE: {0}", release.ToString())

    For Each asset As GitHubAsset In release.Assets
        Console.WriteLine("ASSET  : {0}", asset.ToString())
    Next asset
    Console.WriteLine()
Next release
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GitHub_GitHubUtil">GitHubUtil Class</a><br /><a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />