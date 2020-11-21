# GitHubRelease.Version Property 
 

Gets the release version.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Version Version { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Version As Version
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As GitHubRelease
Dim value As Version

value = instance.Version

```

**C++**<br />
``` C++
public:
property Version^ Version {
	Version^ get ();
}
```

**F#**<br />
``` F#
member Version : Version with get

```


#### Property Value
Type: Version<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.GitHub.GitHubRelease.Version"\]

## Remarks
The version is derived from <a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_TagName">TagName</a>, which should follow semantic versioning guidelines. 

 See for more info about semantic versioning: 

<a href="https://semver.org/" target="_blank">https://semver.org/</a><a href="https://help.github.com/articles/about-releases/" target="_blank">https://help.github.com/articles/about-releases/</a><a href="https://git-scm.com/book/en/v2/Git-Basics-Tagging" target="_blank">https://git-scm.com/book/en/v2/Git-Basics-Tagging</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GitHub_GitHubRelease">GitHubRelease Class</a><br /><a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />