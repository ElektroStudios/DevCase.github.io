# MkvMergeWrapper.VideoContainsTrackType Method 
 

Determines whether the source video file contains the specified type of track.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MkvToolnix">DevCase.ThirdParty.MkvToolnix</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool VideoContainsTrackType(
	string filepath,
	MkvTrackType trackType
)
```

**VB**<br />
``` VB
Public Function VideoContainsTrackType ( 
	filepath As String,
	trackType As MkvTrackType
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As MkvMergeWrapper
Dim filepath As String
Dim trackType As MkvTrackType
Dim returnValue As Boolean

returnValue = instance.VideoContainsTrackType(filepath, 
	trackType)
```

**C++**<br />
``` C++
public:
bool VideoContainsTrackType(
	String^ filepath, 
	MkvTrackType trackType
)
```

**F#**<br />
``` F#
member VideoContainsTrackType : 
        filepath : string * 
        trackType : MkvTrackType -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source video filepath.</dd><dt>trackType</dt><dd>Type: <a href="T_DevCase_ThirdParty_MkvToolnix_MkvTrackType">DevCase.ThirdParty.MkvToolnix.MkvTrackType</a><br />The track type to find.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the source video file contains the specified type of track, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper">MkvMergeWrapper Class</a><br /><a href="N_DevCase_ThirdParty_MkvToolnix">DevCase.ThirdParty.MkvToolnix Namespace</a><br />