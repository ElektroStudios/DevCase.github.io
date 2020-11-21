# LibVideoUtil.GetVideos Method 
 

Gets a YouTubeVideo array containing the info of the downloadable videos of the specified Youtube video Url.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_LibVideo">DevCase.ThirdParty.LibVideo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static YouTubeVideo[] GetVideos(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function GetVideos ( 
	url As String
) As YouTubeVideo()
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As YouTubeVideo()

returnValue = LibVideoUtil.GetVideos(url)
```

**C++**<br />
``` C++
public:
static array<YouTubeVideo^>^ GetVideos(
	String^ url
)
```

**F#**<br />
``` F#
static member GetVideos : 
        url : string -> YouTubeVideo[] 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Youtube video Url.</dd></dl>

#### Return Value
Type: YouTubeVideo[]<br />A YouTubeVideo array containing the info of the downloadable videos of the specified Youtube video Url.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_LibVideo_LibVideoUtil">LibVideoUtil Class</a><br /><a href="N_DevCase_ThirdParty_LibVideo">DevCase.ThirdParty.LibVideo Namespace</a><br />