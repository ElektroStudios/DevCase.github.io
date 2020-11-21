# MediaInfoFile.FieldCount Property 
 

Gets the count of information fields available in the specified stream of the open file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int this[
	StreamType streamType,
	int streamNumber
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property FieldCount ( 
	streamType As StreamType,
	streamNumber As Integer
) As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MediaInfoFile
Dim streamType As StreamType
Dim streamNumber As Integer
Dim value As Integer

value = instance.FieldCount(streamType, 
	streamNumber)

```

**C++**<br />
``` C++
public:
property int FieldCount[StreamType streamType, int streamNumber] {
	int get (StreamType streamType, int streamNumber);
}
```

**F#**<br />
``` F#
member FieldCount : int with get

```


#### Parameters
&nbsp;<dl><dt>streamType</dt><dd>Type: <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">DevCase.ThirdParty.MediaInfo.StreamType</a><br />The kind of stream (general, video, audio, etc...)</dd><dt>streamNumber</dt><dd>Type: System.Int32<br />The stream number in the specified kind of stream of *streamType*. 

 (the 1st audio track, 2nd audio track, etc...)</dd></dl>

#### Property Value
Type: Int32<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.MediaInfo.MediaInfoFile.FieldCount(DevCase.ThirdParty.MediaInfo.StreamType,System.Int32)"\]

#### Return Value
Type: Int32<br />The count of information fields available in the specified stream of the open file.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MediaInfo_MediaInfoFile">MediaInfoFile Class</a><br /><a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo Namespace</a><br />