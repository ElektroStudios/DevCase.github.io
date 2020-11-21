# MediaInfoFile.Fields Property (StreamType, Fields)
 

Gets the value of the specified information field in the open file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string this[
	StreamType streamType,
	Fields field
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Fields ( 
	streamType As StreamType,
	field As Fields
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MediaInfoFile
Dim streamType As StreamType
Dim field As Fields
Dim value As String

value = instance.Fields(streamType, field)

```

**C++**<br />
``` C++
public:
property String^ Fields[StreamType streamType, Fields field] {
	String^ get (StreamType streamType, Fields field);
}
```

**F#**<br />
``` F#
member Fields : string with get

```


#### Parameters
&nbsp;<dl><dt>streamType</dt><dd>Type: <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">DevCase.ThirdParty.MediaInfo.StreamType</a><br />The kind of stream (general, video, audio, etc...)</dd><dt>field</dt><dd>Type: <a href="T_DevCase_ThirdParty_MediaInfo_Fields">DevCase.ThirdParty.MediaInfo.Fields</a><br />The information field to retrieve.</dd></dl>

#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.MediaInfo.MediaInfoFile.Fields(DevCase.ThirdParty.MediaInfo.StreamType,DevCase.ThirdParty.MediaInfo.Fields)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MediaInfo_MediaInfoFile">MediaInfoFile Class</a><br /><a href="Overload_DevCase_ThirdParty_MediaInfo_MediaInfoFile_Fields">Fields Overload</a><br /><a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo Namespace</a><br />