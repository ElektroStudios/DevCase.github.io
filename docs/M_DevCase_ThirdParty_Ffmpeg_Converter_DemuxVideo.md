# Converter.DemuxVideo Method 
 

Demuxes the video track of a video file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int DemuxVideo(
	string inputFilepath,
	string outputFilepath,
	bool overWrite,
	int threads = 1
)
```

**VB**<br />
``` VB
Public Function DemuxVideo ( 
	inputFilepath As String,
	outputFilepath As String,
	overWrite As Boolean,
	Optional threads As Integer = 1
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim inputFilepath As String
Dim outputFilepath As String
Dim overWrite As Boolean
Dim threads As Integer
Dim returnValue As Integer

returnValue = instance.DemuxVideo(inputFilepath, 
	outputFilepath, overWrite, threads)
```

**C++**<br />
``` C++
public:
int DemuxVideo(
	String^ inputFilepath, 
	String^ outputFilepath, 
	bool overWrite, 
	int threads = 1
)
```

**F#**<br />
``` F#
member DemuxVideo : 
        inputFilepath : string * 
        outputFilepath : string * 
        overWrite : bool * 
        ?threads : int 
(* Defaults:
        let _threads = defaultArg threads 1
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>inputFilepath</dt><dd>Type: System.String<br />The source video filepath.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The target video filepath.</dd><dt>overWrite</dt><dd>Type: System.Boolean<br />A value indicating whether to overwrite the target filepath if already exists.</dd><dt>threads (Optional)</dt><dd>Type: System.Int32<br />The amount of threads to use. 

 Default value is `1`.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg Namespace</a><br />