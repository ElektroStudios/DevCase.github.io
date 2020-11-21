# WebUtil.GetHttpResponse Method (String)
 

Gets the Http response of an Http request.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static HttpWebResponse GetHttpResponse(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function GetHttpResponse ( 
	url As String
) As HttpWebResponse
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As HttpWebResponse

returnValue = WebUtil.GetHttpResponse(url)
```

**C++**<br />
``` C++
public:
static HttpWebResponse^ GetHttpResponse(
	String^ url
)
```

**F#**<br />
``` F#
static member GetHttpResponse : 
        url : string -> HttpWebResponse 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to request.</dd></dl>

#### Return Value
Type: HttpWebResponse<br />The HttpWebResponse.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim response As HttpWebResponse = GetHttpResponse("http://www.google.com/StatusCode404")

If response.StatusCode = HttpStatusCode.NotFound Then
    MessageBox.Show("Error 404", "", MessageBoxButtons.OK, MessageBoxIcon.Error)
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_GetHttpResponse">GetHttpResponse Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />