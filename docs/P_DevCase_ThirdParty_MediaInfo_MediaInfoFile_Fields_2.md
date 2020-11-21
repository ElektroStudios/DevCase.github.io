# MediaInfoFile.Fields Property (StreamType, Int32, String)
 

Gets the value of the specified information field in the open file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string this[
	StreamType streamType,
	int streamNumber,
	string fieldName
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Fields ( 
	streamType As StreamType,
	streamNumber As Integer,
	fieldName As String
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MediaInfoFile
Dim streamType As StreamType
Dim streamNumber As Integer
Dim fieldName As String
Dim value As String

value = instance.Fields(streamType, streamNumber, 
	fieldName)

```

**C++**<br />
``` C++
public:
property String^ Fields[StreamType streamType, int streamNumber, String^ fieldName] {
	String^ get (StreamType streamType, int streamNumber, String^ fieldName);
}
```

**F#**<br />
``` F#
member Fields : string with get

```


#### Parameters
&nbsp;<dl><dt>streamType</dt><dd>Type: <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">DevCase.ThirdParty.MediaInfo.StreamType</a><br />The kind of stream (general, video, audio, etc...)</dd><dt>streamNumber</dt><dd>Type: System.Int32<br />The stream number in the specified kind of stream of *streamType*. 

 (the 1st audio track, 2nd audio track, etc...)</dd><dt>fieldName</dt><dd>Type: System.String<br />The name of the information field to retrieve.</dd></dl>

#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.MediaInfo.MediaInfoFile.Fields(DevCase.ThirdParty.MediaInfo.StreamType,System.Int32,System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MediaInfo_MediaInfoFile">MediaInfoFile Class</a><br /><a href="Overload_DevCase_ThirdParty_MediaInfo_MediaInfoFile_Fields">Fields Overload</a><br /><a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo Namespace</a><br />