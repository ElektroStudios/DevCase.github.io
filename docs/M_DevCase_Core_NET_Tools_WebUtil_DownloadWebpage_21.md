# WebUtil.DownloadWebpage Method (Uri, String, Encoding)
 

Downloads the source-code of an Url that points to an Html document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DownloadWebpage(
	Uri uri,
	string userAgent,
	Encoding enc
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpage ( 
	uri As Uri,
	userAgent As String,
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim userAgent As String
Dim enc As Encoding
Dim returnValue As String

returnValue = WebUtil.DownloadWebpage(uri, 
	userAgent, enc)
```

**C++**<br />
``` C++
public:
static String^ DownloadWebpage(
	Uri^ uri, 
	String^ userAgent, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
static member DownloadWebpage : 
        uri : Uri * 
        userAgent : string * 
        enc : Encoding -> string 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri address.</dd><dt>userAgent</dt><dd>Type: System.String<br />Specifies a custom user-agent to perform the web request.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The Encoding used to read the webpage.</dd></dl>

#### Return Value
Type: String<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim html As String = DownloadWebpage(New Uri("http://www.elhacker.net/"), "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)", Encoding.UTF8)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpage">DownloadWebpage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />