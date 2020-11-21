# MediaInfoFile.StreamCount Property (StreamType)
 

Gets the count of streams of the specified <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">StreamType</a> type in the open file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int this[
	StreamType streamType
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property StreamCount ( 
	streamType As StreamType
) As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MediaInfoFile
Dim streamType As StreamType
Dim value As Integer

value = instance.StreamCount(streamType)

```

**C++**<br />
``` C++
public:
property int StreamCount[StreamType streamType] {
	int get (StreamType streamType);
}
```

**F#**<br />
``` F#
member StreamCount : int with get

```


#### Parameters
&nbsp;<dl><dt>streamType</dt><dd>Type: <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">DevCase.ThirdParty.MediaInfo.StreamType</a><br />The kind of stream (general, video, audio, etc...)</dd></dl>

#### Property Value
Type: Int32<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.MediaInfo.MediaInfoFile.StreamCount(DevCase.ThirdParty.MediaInfo.StreamType)"\]

#### Return Value
Type: Int32<br />The count of streams of the specified <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">StreamType</a> type in the open file.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MediaInfo_MediaInfoFile">MediaInfoFile Class</a><br /><a href="Overload_DevCase_ThirdParty_MediaInfo_MediaInfoFile_StreamCount">StreamCount Overload</a><br /><a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo Namespace</a><br />