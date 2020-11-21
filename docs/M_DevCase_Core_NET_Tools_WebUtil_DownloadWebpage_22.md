# WebUtil.DownloadWebpage Method (Uri, Encoding)
 

Downloads the source-code of an Url that points to an Html document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DownloadWebpage(
	Uri uri,
	Encoding enc
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpage ( 
	uri As Uri,
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim enc As Encoding
Dim returnValue As String

returnValue = WebUtil.DownloadWebpage(uri, 
	enc)
```

**C++**<br />
``` C++
public:
static String^ DownloadWebpage(
	Uri^ uri, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
static member DownloadWebpage : 
        uri : Uri * 
        enc : Encoding -> string 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri address.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The Encoding used to read the webpage.</dd></dl>

#### Return Value
Type: String<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim html As String = DownloadWebpage(New Uri("http://www.elhacker.net/"), Encoding.UTF8)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpage">DownloadWebpage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />