# WebUtil.GetPostResponse Method (Uri, NameValueCollection)
 

Sends a POST method request and returns the server response.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] GetPostResponse(
	Uri uri,
	NameValueCollection postData
)
```

**VB**<br />
``` VB
Public Shared Function GetPostResponse ( 
	uri As Uri,
	postData As NameValueCollection
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim postData As NameValueCollection
Dim returnValue As Byte()

returnValue = WebUtil.GetPostResponse(uri, 
	postData)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ GetPostResponse(
	Uri^ uri, 
	NameValueCollection^ postData
)
```

**F#**<br />
``` F#
static member GetPostResponse : 
        uri : Uri * 
        postData : NameValueCollection -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri.</dd><dt>postData</dt><dd>Type: System.Collections.Specialized.NameValueCollection<br />The post data.</dd></dl>

#### Return Value
Type: Byte[]<br />The response content.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim params As New Specialized.NameValueCollection() From {
    {"search", "Petición+POST"},
    {"sourceid", "Mozilla-search"}
} ' Formated POST Data: "search=Petición+POST&sourceid=Mozilla-search"

Dim response As Byte() = GetPostResponse(New Uri("http://es.wikipedia.org/wiki/Special:Search?"), params)
Dim str As String = Encoding.Default.GetString(response)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_GetPostResponse">GetPostResponse Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />