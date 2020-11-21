# ImgurUtil.GetThumbnailUrl Method (String, ThumbnailType)
 

Given a Imgur's image url, returns the corresponding url that points to the specified thumbnail type.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetThumbnailUrl(
	string imageUrl,
	ThumbnailType thumbnailType
)
```

**VB**<br />
``` VB
Public Shared Function GetThumbnailUrl ( 
	imageUrl As String,
	thumbnailType As ThumbnailType
) As String
```

**VB Usage**<br />
``` VB Usage
Dim imageUrl As String
Dim thumbnailType As ThumbnailType
Dim returnValue As String

returnValue = ImgurUtil.GetThumbnailUrl(imageUrl, 
	thumbnailType)
```

**C++**<br />
``` C++
public:
static String^ GetThumbnailUrl(
	String^ imageUrl, 
	ThumbnailType thumbnailType
)
```

**F#**<br />
``` F#
static member GetThumbnailUrl : 
        imageUrl : string * 
        thumbnailType : ThumbnailType -> string 

```


#### Parameters
&nbsp;<dl><dt>imageUrl</dt><dd>Type: System.String<br />The image url.</dd><dt>thumbnailType</dt><dd>Type: <a href="T_DevCase_ThirdParty_Imgur_ThumbnailType">DevCase.ThirdParty.Imgur.ThumbnailType</a><br />The type of thumbnail url to retrieve.</dd></dl>

#### Return Value
Type: String<br />The resulting thumbnail's url. .

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Imgur_ImgurUtil">ImgurUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_Imgur_ImgurUtil_GetThumbnailUrl">GetThumbnailUrl Overload</a><br /><a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur Namespace</a><br />