# WebUtil.GetPostResponse Method (Uri, Dictionary(String, String))
 

Sends a POST method request and returns the server response.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] GetPostResponse(
	Uri uri,
	Dictionary<string, string> postData
)
```

**VB**<br />
``` VB
Public Shared Function GetPostResponse ( 
	uri As Uri,
	postData As Dictionary(Of String, String)
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim postData As Dictionary(Of String, String)
Dim returnValue As Byte()

returnValue = WebUtil.GetPostResponse(uri, 
	postData)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ GetPostResponse(
	Uri^ uri, 
	Dictionary<String^, String^>^ postData
)
```

**F#**<br />
``` F#
static member GetPostResponse : 
        uri : Uri * 
        postData : Dictionary<string, string> -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri.</dd><dt>postData</dt><dd>Type: System.Collections.Generic.Dictionary(String, String)<br />The post data.</dd></dl>

#### Return Value
Type: Byte[]<br />The response content.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim response As Byte() = GetPostResponse(New Uri("http://es.wikipedia.org/wiki/Special:Search?"),
             New Dictionary(Of String, String) From {
                 {"search", "Petición+POST"},
                 {"sourceid", "Mozilla-search"}
             }) ' Formated POST Data: "search=Petición+POST&sourceid=Mozilla-search"

Dim str As String = Encoding.Default.GetString(response)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_GetPostResponse">GetPostResponse Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />