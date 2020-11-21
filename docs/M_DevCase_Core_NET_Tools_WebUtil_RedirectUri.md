# WebUtil.RedirectUri Method (String)
 

Redirects an Url that points to other Url.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Uri RedirectUri(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function RedirectUri ( 
	url As String
) As Uri
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As Uri

returnValue = WebUtil.RedirectUri(url)
```

**C++**<br />
``` C++
public:
static Uri^ RedirectUri(
	String^ url
)
```

**F#**<br />
``` F#
static member RedirectUri : 
        url : string -> Uri 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to redirect.</dd></dl>

#### Return Value
Type: Uri<br />The redirected Url.

## Remarks
Url redirection, also called Url forwarding, is a World Wide Web technique for making a web page available under more than one Url address. 

 When a web browser attempts to open a Url that has been redirected, a page with a different Url is opened.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim url As String = "http://goo.gl/PsCZN4"
Dim resultUri As Uri = RedirectUri(url)

Console.WriteLine(resultUri.AbsoluteUri)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_RedirectUri">RedirectUri Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />