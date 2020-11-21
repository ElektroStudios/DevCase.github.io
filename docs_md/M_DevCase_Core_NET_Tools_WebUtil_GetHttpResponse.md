# WebUtil.GetHttpResponse Method (HttpWebRequest)
 

Gets the response of an Http request.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static HttpWebResponse GetHttpResponse(
	HttpWebRequest request
)
```

**VB**<br />
``` VB
Public Shared Function GetHttpResponse ( 
	request As HttpWebRequest
) As HttpWebResponse
```

**VB Usage**<br />
``` VB Usage
Dim request As HttpWebRequest
Dim returnValue As HttpWebResponse

returnValue = WebUtil.GetHttpResponse(request)
```

**C++**<br />
``` C++
public:
static HttpWebResponse^ GetHttpResponse(
	HttpWebRequest^ request
)
```

**F#**<br />
``` F#
static member GetHttpResponse : 
        request : HttpWebRequest -> HttpWebResponse 

```


#### Parameters
&nbsp;<dl><dt>request</dt><dd>Type: System.Net.HttpWebRequest<br />The request.</dd></dl>

#### Return Value
Type: HttpWebResponse<br />The HttpWebResponse.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim response As HttpWebResponse = GetHttpResponse(WebRequest.Create("http://www.google.com/StatusCode404"))

If response.StatusCode = HttpStatusCode.NotFound Then
    MessageBox.Show("Error 404", "", MessageBoxButtons.OK, MessageBoxIcon.Error)
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_GetHttpResponse">GetHttpResponse Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />