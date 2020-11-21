# GitHubAsset Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_GitHub_GitHubAsset">GitHubAsset</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public GitHubAsset(
	XElement xml
)
```

**VB**<br />
``` VB
Public Sub New ( 
	xml As XElement
)
```

**VB Usage**<br />
``` VB Usage
Dim xml As XElement

Dim instance As New GitHubAsset(xml)
```

**C++**<br />
``` C++
public:
GitHubAsset(
	XElement^ xml
)
```

**F#**<br />
``` F#
new : 
        xml : XElement -> GitHubAsset
```


#### Parameters
&nbsp;<dl><dt>xml</dt><dd>Type: System.Xml.Linq.XElement<br />An XElement that contains the fields to parse. 

 See: <a href="https://api.github.com/repos/{user}/{repo}/releases" target="_blank">https://api.github.com/repos/{user}/{repo}/releases</a></dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GitHub_GitHubAsset">GitHubAsset Class</a><br /><a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />