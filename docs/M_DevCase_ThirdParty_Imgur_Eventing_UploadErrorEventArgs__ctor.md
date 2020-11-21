# UploadErrorEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_Imgur_Eventing_UploadErrorEventArgs">UploadErrorEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur_Eventing">DevCase.ThirdParty.Imgur.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public UploadErrorEventArgs(
	ImgurStatus status,
	string errorMessage
)
```

**VB**<br />
``` VB
Public Sub New ( 
	status As ImgurStatus,
	errorMessage As String
)
```

**VB Usage**<br />
``` VB Usage
Dim status As ImgurStatus
Dim errorMessage As String

Dim instance As New UploadErrorEventArgs(status, 
	errorMessage)
```

**C++**<br />
``` C++
public:
UploadErrorEventArgs(
	ImgurStatus status, 
	String^ errorMessage
)
```

**F#**<br />
``` F#
new : 
        status : ImgurStatus * 
        errorMessage : string -> UploadErrorEventArgs
```


#### Parameters
&nbsp;<dl><dt>status</dt><dd>Type: <a href="T_DevCase_ThirdParty_Imgur_ImgurStatus">DevCase.ThirdParty.Imgur.ImgurStatus</a><br />The Imgur's response status.</dd><dt>errorMessage</dt><dd>Type: System.String<br />The Imgur's response message.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Imgur_Eventing_UploadErrorEventArgs">UploadErrorEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_Imgur_Eventing">DevCase.ThirdParty.Imgur.Eventing Namespace</a><br />