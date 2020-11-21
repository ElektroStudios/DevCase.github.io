# WebUtil.GetPostResponseAsync Method (String, Dictionary(String, String))
 

Asynchronously sends a POST method request and returns the server response.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<byte[]> GetPostResponseAsync(
	string url,
	Dictionary<string, string> postData
)
```

**VB**<br />
``` VB
Public Shared Function GetPostResponseAsync ( 
	url As String,
	postData As Dictionary(Of String, String)
) As Task(Of Byte())
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim postData As Dictionary(Of String, String)
Dim returnValue As Task(Of Byte())

returnValue = WebUtil.GetPostResponseAsync(url, 
	postData)
```

**C++**<br />
``` C++
public:
static Task<array<unsigned char>^>^ GetPostResponseAsync(
	String^ url, 
	Dictionary<String^, String^>^ postData
)
```

**F#**<br />
``` F#
static member GetPostResponseAsync : 
        url : string * 
        postData : Dictionary<string, string> -> Task<byte[]> 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url.</dd><dt>postData</dt><dd>Type: System.Collections.Generic.Dictionary(String, String)<br />The post data.</dd></dl>

#### Return Value
Type: Task(Byte[])<br />The response content.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim response As Byte() =
    Await GetPostResponseAsync("http://es.wikipedia.org/wiki/Special:Search?",
                               New Dictionary(Of String, String) From {
                                   {"search", "Petición+POST"},
                                   {"sourceid", "Mozilla-search"}
                               }) ' Formated POST Data: "search=Petición+POST&sourceid=Mozilla-search"

Dim str As String = Await Encoding.Default.GetString(response)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_GetPostResponseAsync">GetPostResponseAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />