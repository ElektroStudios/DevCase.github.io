# Converter.VideoContainsMetadata Method 
 

Determines whether a video file contains metadata fields.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool VideoContainsMetadata(
	string videoFilepath
)
```

**VB**<br />
``` VB
Public Function VideoContainsMetadata ( 
	videoFilepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim videoFilepath As String
Dim returnValue As Boolean

returnValue = instance.VideoContainsMetadata(videoFilepath)
```

**C++**<br />
``` C++
public:
bool VideoContainsMetadata(
	String^ videoFilepath
)
```

**F#**<br />
``` F#
member VideoContainsMetadata : 
        videoFilepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>videoFilepath</dt><dd>Type: System.String<br />The source video filepath.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if video file contains metadata fields, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg Namespace</a><br />