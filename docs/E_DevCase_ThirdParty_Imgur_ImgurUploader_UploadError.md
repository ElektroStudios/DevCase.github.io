# ImgurUploader.UploadError Event
 

Occurs when Imgur service throws a error response.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<UploadErrorEventArgs> UploadError
```

**VB**<br />
``` VB
Public Event UploadError As EventHandler(Of UploadErrorEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ImgurUploader
Dim handler As EventHandler(Of UploadErrorEventArgs)

AddHandler instance.UploadError, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<UploadErrorEventArgs^>^ UploadError {
	void add (EventHandler<UploadErrorEventArgs^>^ value);
	void remove (EventHandler<UploadErrorEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member UploadError : IEvent<EventHandler<UploadErrorEventArgs>,
    UploadErrorEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_Imgur_Eventing_UploadErrorEventArgs">UploadErrorEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Imgur_ImgurUploader">ImgurUploader Class</a><br /><a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur Namespace</a><br />