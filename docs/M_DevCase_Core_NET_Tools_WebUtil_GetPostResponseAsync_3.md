# WebUtil.GetPostResponseAsync Method (Uri, NameValueCollection)
 

Asynchronously sends a POST method request and returns the server response.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<byte[]> GetPostResponseAsync(
	Uri uri,
	NameValueCollection postData
)
```

**VB**<br />
``` VB
Public Shared Function GetPostResponseAsync ( 
	uri As Uri,
	postData As NameValueCollection
) As Task(Of Byte())
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim postData As NameValueCollection
Dim returnValue As Task(Of Byte())

returnValue = WebUtil.GetPostResponseAsync(uri, 
	postData)
```

**C++**<br />
``` C++
public:
static Task<array<unsigned char>^>^ GetPostResponseAsync(
	Uri^ uri, 
	NameValueCollection^ postData
)
```

**F#**<br />
``` F#
static member GetPostResponseAsync : 
        uri : Uri * 
        postData : NameValueCollection -> Task<byte[]> 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri.</dd><dt>postData</dt><dd>Type: System.Collections.Specialized.NameValueCollection<br />The post data.</dd></dl>

#### Return Value
Type: Task(Byte[])<br />The response content.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim params As New Specialized.NameValueCollection() From {
    {"search", "Petición+POST"},
    {"sourceid", "Mozilla-search"}
} ' Formated POST Data: "search=Petición+POST&sourceid=Mozilla-search"

Dim response As Byte() = Await GetPostResponseAsync(New Uri("http://es.wikipedia.org/wiki/Special:Search?"), params)
Dim str As String = Await Encoding.Default.GetString(response)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_GetPostResponseAsync">GetPostResponseAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />