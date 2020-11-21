# WebUtil.GetMimeTypeExtension Method 
 

Gets the file-extension that is associated to the specified MIME type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetMimeTypeExtension(
	string mimeType
)
```

**VB**<br />
``` VB
Public Shared Function GetMimeTypeExtension ( 
	mimeType As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim mimeType As String
Dim returnValue As String

returnValue = WebUtil.GetMimeTypeExtension(mimeType)
```

**C++**<br />
``` C++
public:
static String^ GetMimeTypeExtension(
	String^ mimeType
)
```

**F#**<br />
``` F#
static member GetMimeTypeExtension : 
        mimeType : string -> string 

```


#### Parameters
&nbsp;<dl><dt>mimeType</dt><dd>Type: System.String<br />The name of the MIME type.</dd></dl>

#### Return Value
Type: String<br />The file-extension.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>mimeType</td></tr><tr><td>ArgumentException</td><td>Requested mime type is not registered: mimeType</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ext As String = GetMimeTypeExtension(mimeType:="application/zip")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />