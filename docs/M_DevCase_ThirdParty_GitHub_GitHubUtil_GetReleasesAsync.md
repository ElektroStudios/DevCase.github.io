# GitHubUtil.GetReleasesAsync Method 
 

Asynchronously gets the releases from the specified repository on GitHub.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<ReadOnlyCollection<GitHubRelease>> GetReleasesAsync(
	string userName,
	string repositoryName
)
```

**VB**<br />
``` VB
Public Shared Function GetReleasesAsync ( 
	userName As String,
	repositoryName As String
) As Task(Of ReadOnlyCollection(Of GitHubRelease))
```

**VB Usage**<br />
``` VB Usage
Dim userName As String
Dim repositoryName As String
Dim returnValue As Task(Of ReadOnlyCollection(Of GitHubRelease))

returnValue = GitHubUtil.GetReleasesAsync(userName, 
	repositoryName)
```

**C++**<br />
``` C++
public:
static Task<ReadOnlyCollection<GitHubRelease^>^>^ GetReleasesAsync(
	String^ userName, 
	String^ repositoryName
)
```

**F#**<br />
``` F#
static member GetReleasesAsync : 
        userName : string * 
        repositoryName : string -> Task<ReadOnlyCollection<GitHubRelease>> 

```


#### Parameters
&nbsp;<dl><dt>userName</dt><dd>Type: System.String<br />The user name.</dd><dt>repositoryName</dt><dd>Type: System.String<br />The repository name.</dd></dl>

#### Return Value
Type: Task(ReadOnlyCollection(<a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease</a>))<br />A Task(TResult) containing the releases.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>HttpException</td><td>JSON validation error.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim releases As ReadOnlyCollection(Of GitHubRelease) = Await GetReleasesAsync("ElektroStudios", "SmartBotKit")

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