# WebUtil.PostXmlHttpRequest Method (Uri, XDocument, Action(HttpWebRequest))
 

Posts an XML HTTP request to the specified server with default encoding (UTF8), and returns the response.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static XDocument PostXmlHttpRequest(
	Uri uri,
	XDocument xml,
	Action<HttpWebRequest> request
)
```

**VB**<br />
``` VB
Public Shared Function PostXmlHttpRequest ( 
	uri As Uri,
	xml As XDocument,
	request As Action(Of HttpWebRequest)
) As XDocument
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim xml As XDocument
Dim request As Action(Of HttpWebRequest)
Dim returnValue As XDocument

returnValue = WebUtil.PostXmlHttpRequest(uri, 
	xml, request)
```

**C++**<br />
``` C++
public:
static XDocument^ PostXmlHttpRequest(
	Uri^ uri, 
	XDocument^ xml, 
	Action<HttpWebRequest^>^ request
)
```

**F#**<br />
``` F#
static member PostXmlHttpRequest : 
        uri : Uri * 
        xml : XDocument * 
        request : Action<HttpWebRequest> -> XDocument 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The server Uri.</dd><dt>xml</dt><dd>Type: System.Xml.Linq.XDocument<br />A XDocument that represents the XML content to POST to the server.</dd><dt>request</dt><dd>Type: System.Action(HttpWebRequest)<br />A HttpWebRequest object that represents the request parameters and custom header values. 

 (It is not necessary to set the Method and ContentLength properties)</dd></dl>

#### Return Value
Type: XDocument<br />The resulting response returned by the server.

## Examples
This is a code example that demonstrates how to POST a XmlHttpRequest to http://converter.telerik.com/service.asmx service. 
**VB**<br />
``` VB
Dim xml As XDocument =
    <?xml version="1.0" encoding="utf-8"?>
    <soap12:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
        xmlns:xsd="http://www.w3.org/2001/XMLSchema"
        xmlns:soap12="http://www.w3.org/2003/05/soap-envelope">
        <soap12:Body>
            <ConvertToCS xmlns="http://converter.telerik.com">
                <vbCode>Dim str As String = "Hello World"</vbCode>
            </ConvertToCS>
        </soap12:Body>
    </soap12:Envelope>

Dim result As XDocument =
    PostXmlHttpRequest(New Uri("http://converter.telerik.com/service.asmx"), xml,
                       Sub(req As HttpWebRequest)
                           req.Method = "POST"
                           req.Host = "converter.telerik.com"
                           req.ContentType = "application/soap+xml; charset=utf-8"
                           req.UserAgent = "Mozilla/5.0 (Windows NT 6.1; WOW64; rv:40.0) Gecko/20100101 Firefox/40.1"
                           req.Credentials = New NetworkCredential()
                           req.KeepAlive = False
                       End Sub)

Dim ns As XNamespace = result.Root.Name.Namespace
Dim el As XElement = result.Element(ns + "Envelope").Element(ns + "Body")

Console.WriteLine(el.Value)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_PostXmlHttpRequest">PostXmlHttpRequest Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />