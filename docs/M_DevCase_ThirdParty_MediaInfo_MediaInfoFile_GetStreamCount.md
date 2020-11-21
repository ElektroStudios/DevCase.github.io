# MediaInfoFile.GetStreamCount Method 
 

Gets the count of streams of the specified <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">StreamType</a> type in the open file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int GetStreamCount(
	StreamType streamType
)
```

**VB**<br />
``` VB
Public Function GetStreamCount ( 
	streamType As StreamType
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MediaInfoFile
Dim streamType As StreamType
Dim returnValue As Integer

returnValue = instance.GetStreamCount(streamType)
```

**C++**<br />
``` C++
public:
int GetStreamCount(
	StreamType streamType
)
```

**F#**<br />
``` F#
member GetStreamCount : 
        streamType : StreamType -> int 

```


#### Parameters
&nbsp;<dl><dt>streamType</dt><dd>Type: <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">DevCase.ThirdParty.MediaInfo.StreamType</a><br />The kind of stream (general, video, audio, etc...)</dd></dl>

#### Return Value
Type: Int32<br />The count of streams of the specified <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">StreamType</a> type in the open file.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MediaInfo_MediaInfoFile">MediaInfoFile Class</a><br /><a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo Namespace</a><br />