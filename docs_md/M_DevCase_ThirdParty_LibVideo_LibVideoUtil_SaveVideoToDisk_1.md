# LibVideoUtil.SaveVideoToDisk Method (YouTubeVideo, String)
 

Downloads a Youtube video to disk.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_LibVideo">DevCase.ThirdParty.LibVideo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SaveVideoToDisk(
	YouTubeVideo video,
	string dirPath
)
```

**VB**<br />
``` VB
Public Shared Sub SaveVideoToDisk ( 
	video As YouTubeVideo,
	dirPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim video As YouTubeVideo
Dim dirPath As StringLibVideoUtil.SaveVideoToDisk(video, dirPath)
```

**C++**<br />
``` C++
public:
static void SaveVideoToDisk(
	YouTubeVideo^ video, 
	String^ dirPath
)
```

**F#**<br />
``` F#
static member SaveVideoToDisk : 
        video : YouTubeVideo * 
        dirPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>video</dt><dd>Type: YouTubeVideo<br />A YouTubeVideo object containing the video info.</dd><dt>dirPath</dt><dd>Type: System.String<br />The directory path where to save the downloaded video.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_LibVideo_LibVideoUtil">LibVideoUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_LibVideo_LibVideoUtil_SaveVideoToDisk">SaveVideoToDisk Overload</a><br /><a href="N_DevCase_ThirdParty_LibVideo">DevCase.ThirdParty.LibVideo Namespace</a><br />