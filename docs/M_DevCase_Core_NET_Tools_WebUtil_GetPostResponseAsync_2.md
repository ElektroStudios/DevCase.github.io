# WebUtil.GetPostResponseAsync Method (Uri, Dictionary(String, String))
 

Asynchronously sends a POST method request and returns the server response.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<byte[]> GetPostResponseAsync(
	Uri uri,
	Dictionary<string, string> postData
)
```

**VB**<br />
``` VB
Public Shared Function GetPostResponseAsync ( 
	uri As Uri,
	postData As Dictionary(Of String, String)
) As Task(Of Byte())
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim postData As Dictionary(Of String, String)
Dim returnValue As Task(Of Byte())

returnValue = WebUtil.GetPostResponseAsync(uri, 
	postData)
```

**C++**<br />
``` C++
public:
static Task<array<unsigned char>^>^ GetPostResponseAsync(
	Uri^ uri, 
	Dictionary<String^, String^>^ postData
)
```

**F#**<br />
``` F#
static member GetPostResponseAsync : 
        uri : Uri * 
        postData : Dictionary<string, string> -> Task<byte[]> 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri.</dd><dt>postData</dt><dd>Type: System.Collections.Generic.Dictionary(String, String)<br />The post data.</dd></dl>

#### Return Value
Type: Task(Byte[])<br />The response content.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim response As Byte() = Await GetPostResponseAsync(New Uri("http://es.wikipedia.org/wiki/Special:Search?"),
                               New Dictionary(Of String, String) From {
                                   {"search", "Petición+POST"},
                                   {"sourceid", "Mozilla-search"}
                               }) ' Formated POST Data: "search=Petición+POST&sourceid=Mozilla-search"

Dim str As String = Await Encoding.Default.GetString(response)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_GetPostResponseAsync">GetPostResponseAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />