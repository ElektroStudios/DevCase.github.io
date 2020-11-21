# UploadCompletedEventArgs.Result Property 
 

Gets the Imgur's image info.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur_Eventing">DevCase.ThirdParty.Imgur.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ImgurImageInfo Result { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Result As ImgurImageInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As UploadCompletedEventArgs
Dim value As ImgurImageInfo

value = instance.Result

```

**C++**<br />
``` C++
public:
property ImgurImageInfo^ Result {
	ImgurImageInfo^ get ();
}
```

**F#**<br />
``` F#
member Result : ImgurImageInfo with get

```


#### Property Value
Type: <a href="T_DevCase_ThirdParty_Imgur_ImgurImageInfo">ImgurImageInfo</a><br />The Imgur's image info.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Imgur_Eventing_UploadCompletedEventArgs">UploadCompletedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_Imgur_Eventing">DevCase.ThirdParty.Imgur.Eventing Namespace</a><br />