# WebUtil.RedirectUri Method (Uri)
 

Redirects an Url that points to other Url.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Uri RedirectUri(
	Uri uri
)
```

**VB**<br />
``` VB
Public Shared Function RedirectUri ( 
	uri As Uri
) As Uri
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim returnValue As Uri

returnValue = WebUtil.RedirectUri(uri)
```

**C++**<br />
``` C++
public:
static Uri^ RedirectUri(
	Uri^ uri
)
```

**F#**<br />
``` F#
static member RedirectUri : 
        uri : Uri -> Uri 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri to redirect.</dd></dl>

#### Return Value
Type: Uri<br />The redirected Url.

## Remarks
Url redirection, also called Url forwarding, is a World Wide Web technique for making a web page available under more than one Url address. 

 When a web browser attempts to open a Url that has been redirected, a page with a different Url is opened.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim uri As New Uri("http://goo.gl/PsCZN4")
Dim resultUri As Uri = RedirectUri(uri)

Console.WriteLine(resultUri.AbsoluteUri)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_RedirectUri">RedirectUri Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />