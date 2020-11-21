# UploadErrorEventArgs.Status Property 
 

Gets the Imgur's response status.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur_Eventing">DevCase.ThirdParty.Imgur.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ImgurStatus Status { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Status As ImgurStatus
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As UploadErrorEventArgs
Dim value As ImgurStatus

value = instance.Status

```

**C++**<br />
``` C++
public:
property ImgurStatus Status {
	ImgurStatus get ();
}
```

**F#**<br />
``` F#
member Status : ImgurStatus with get

```


#### Property Value
Type: <a href="T_DevCase_ThirdParty_Imgur_ImgurStatus">ImgurStatus</a><br />The Imgur's response status.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Imgur_Eventing_UploadErrorEventArgs">UploadErrorEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_Imgur_Eventing">DevCase.ThirdParty.Imgur.Eventing Namespace</a><br />