# WebUtil.GetMimeType Method 
 

Gets the name of the MIME type of the specified file-extension.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetMimeType(
	string fileExtension
)
```

**VB**<br />
``` VB
Public Shared Function GetMimeType ( 
	fileExtension As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim fileExtension As String
Dim returnValue As String

returnValue = WebUtil.GetMimeType(fileExtension)
```

**C++**<br />
``` C++
public:
static String^ GetMimeType(
	String^ fileExtension
)
```

**F#**<br />
``` F#
static member GetMimeType : 
        fileExtension : string -> string 

```


#### Parameters
&nbsp;<dl><dt>fileExtension</dt><dd>Type: System.String<br />The file extension.</dd></dl>

#### Return Value
Type: String<br />The name of the MIME type of the specified file-extension. 

 If the specified file-extension is not found, then `application/octet-stream` MIME is returned.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>fileExtension</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mime As String = GetMimeType(fileExtension:=".zip")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />