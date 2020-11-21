# WebUtil.MimeTypes Property 
 

Gets a collection of known MIME types and its file-extensions.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Dictionary<string, string> MimeTypes { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property MimeTypes As Dictionary(Of String, String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Dictionary(Of String, String)

value = WebUtil.MimeTypes

```

**C++**<br />
``` C++
public:
static property Dictionary<String^, String^>^ MimeTypes {
	Dictionary<String^, String^>^ get ();
}
```

**F#**<br />
``` F#
static member MimeTypes : Dictionary<string, string> with get

```


#### Property Value
Type: Dictionary(String, String)<br />A Dictionary(TKey, TValue) that contains the file extensions and MIME types.

## Remarks
Original source: <a href="http://github.com/samuelneff/MimeTypeMap/blob/master/src/MimeTypes/MimeTypeMap.cs" target="_blank">http://github.com/samuelneff/MimeTypeMap/blob/master/src/MimeTypes/MimeTypeMap.cs</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mime As String = MimeTypes(key:=".zip")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />