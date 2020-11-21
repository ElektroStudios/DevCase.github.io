# ImgurUploader.UploadImageAsync Method 
 

Uploads a image, Asynchronously.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ImgurImageInfo UploadImageAsync(
	string filepath
)
```

**VB**<br />
``` VB
Public Function UploadImageAsync ( 
	filepath As String
) As ImgurImageInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As ImgurUploader
Dim filepath As String
Dim returnValue As ImgurImageInfo

returnValue = instance.UploadImageAsync(filepath)
```

**C++**<br />
``` C++
public:
ImgurImageInfo^ UploadImageAsync(
	String^ filepath
)
```

**F#**<br />
``` F#
member UploadImageAsync : 
        filepath : string -> ImgurImageInfo 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The image filepath to upload.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_ThirdParty_Imgur_ImgurImageInfo">ImgurImageInfo</a><br />A <a href="T_DevCase_ThirdParty_Imgur_ImgurImageInfo">ImgurImageInfo</a> instance that contains the resulting image url.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Imgur_ImgurUploader">ImgurUploader Class</a><br /><a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur Namespace</a><br />