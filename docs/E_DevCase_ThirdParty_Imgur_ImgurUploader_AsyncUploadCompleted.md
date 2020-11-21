# ImgurUploader.AsyncUploadCompleted Event
 

Occurs when the image uploading is completed.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<UploadCompletedEventArgs> AsyncUploadCompleted
```

**VB**<br />
``` VB
Public Event AsyncUploadCompleted As EventHandler(Of UploadCompletedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ImgurUploader
Dim handler As EventHandler(Of UploadCompletedEventArgs)

AddHandler instance.AsyncUploadCompleted, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<UploadCompletedEventArgs^>^ AsyncUploadCompleted {
	void add (EventHandler<UploadCompletedEventArgs^>^ value);
	void remove (EventHandler<UploadCompletedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member AsyncUploadCompleted : IEvent<EventHandler<UploadCompletedEventArgs>,
    UploadCompletedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_Imgur_Eventing_UploadCompletedEventArgs">UploadCompletedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Imgur_ImgurUploader">ImgurUploader Class</a><br /><a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur Namespace</a><br />