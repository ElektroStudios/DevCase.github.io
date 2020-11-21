# WebUtil.DownloadFileAsync Method (WebProxy, String, String, String, DownloadProgressChangedEventHandler, AsyncCompletedEventHandler)
 

Asynchronously downloads a file to the specified filepath, using the specified proxy.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DownloadFileAsync(
	WebProxy proxy,
	string url,
	string dirpath,
	string filename,
	DownloadProgressChangedEventHandler callbackDownloadProgressChanged,
	AsyncCompletedEventHandler callbackDownloadFileCompleted
)
```

**VB**<br />
``` VB
Public Shared Sub DownloadFileAsync ( 
	proxy As WebProxy,
	url As String,
	dirpath As String,
	filename As String,
	callbackDownloadProgressChanged As DownloadProgressChangedEventHandler,
	callbackDownloadFileCompleted As AsyncCompletedEventHandler
)
```

**VB Usage**<br />
``` VB Usage
Dim proxy As WebProxy
Dim url As String
Dim dirpath As String
Dim filename As String
Dim callbackDownloadProgressChanged As DownloadProgressChangedEventHandler
Dim callbackDownloadFileCompleted As AsyncCompletedEventHandlerWebUtil.DownloadFileAsync(proxy, url, 
	dirpath, filename, callbackDownloadProgressChanged, 
	callbackDownloadFileCompleted)
```

**C++**<br />
``` C++
public:
static void DownloadFileAsync(
	WebProxy^ proxy, 
	String^ url, 
	String^ dirpath, 
	String^ filename, 
	DownloadProgressChangedEventHandler^ callbackDownloadProgressChanged, 
	AsyncCompletedEventHandler^ callbackDownloadFileCompleted
)
```

**F#**<br />
``` F#
static member DownloadFileAsync : 
        proxy : WebProxy * 
        url : string * 
        dirpath : string * 
        filename : string * 
        callbackDownloadProgressChanged : DownloadProgressChangedEventHandler * 
        callbackDownloadFileCompleted : AsyncCompletedEventHandler -> unit 

```


#### Parameters
&nbsp;<dl><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>dirpath</dt><dd>Type: System.String<br />The target directory path.</dd><dt>filename</dt><dd>Type: System.String<br />The target filename.</dd><dt>callbackDownloadProgressChanged</dt><dd>Type: System.Net.DownloadProgressChangedEventHandler<br />A callback to report the download progress.</dd><dt>callbackDownloadFileCompleted</dt><dd>Type: System.ComponentModel.AsyncCompletedEventHandler<br />A callback to report the download completition.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Sub Test()

    Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
    proxy.Credentials = New NetworkCredential("user", "pass")
    DownloadFile(proxy, "http://download.thinkbroadband.com/5MB.zip", "C:\", "5MB.zip",
                 AddressOf DownloadProgressChanged,
                 AddressOf DownloadFileCompleted)

End Sub

Public Sub DownloadProgressChanged(ByVal sender As Object, ByVal e As DownloadProgressChangedEventArgs)

    Debug.WriteLine(e.BytesReceived)

End Sub

Public Sub DownloadFileCompleted(ByVal sender As Object, ByVal e As AsyncCompletedEventArgs)

    If (e.Error IsNot Nothing) Then
        MessageBox.Show(e.Error.Message, "Error", MessageBoxButtons.OK, MessageBoxIcon.Error)

    Else
        MessageBox.Show("Download completed.", "", MessageBoxButtons.OK, MessageBoxIcon.Information)

    End If

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadFileAsync">DownloadFileAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />