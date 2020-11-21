# Converter.RecompressAudio Method 
 

ReCompress the audio track of a video file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int RecompressAudio(
	string inputFilepath,
	string outputFilepath,
	bool overWrite,
	FFMPEGAudioCodec audioCodec,
	FfmpegAudioBitrate bitrate,
	bool preserveMetadata = false,
	int threads = 1
)
```

**VB**<br />
``` VB
Public Function RecompressAudio ( 
	inputFilepath As String,
	outputFilepath As String,
	overWrite As Boolean,
	audioCodec As FFMPEGAudioCodec,
	bitrate As FfmpegAudioBitrate,
	Optional preserveMetadata As Boolean = false,
	Optional threads As Integer = 1
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim inputFilepath As String
Dim outputFilepath As String
Dim overWrite As Boolean
Dim audioCodec As FFMPEGAudioCodec
Dim bitrate As FfmpegAudioBitrate
Dim preserveMetadata As Boolean
Dim threads As Integer
Dim returnValue As Integer

returnValue = instance.RecompressAudio(inputFilepath, 
	outputFilepath, overWrite, audioCodec, 
	bitrate, preserveMetadata, threads)
```

**C++**<br />
``` C++
public:
int RecompressAudio(
	String^ inputFilepath, 
	String^ outputFilepath, 
	bool overWrite, 
	FFMPEGAudioCodec audioCodec, 
	FfmpegAudioBitrate bitrate, 
	bool preserveMetadata = false, 
	int threads = 1
)
```

**F#**<br />
``` F#
member RecompressAudio : 
        inputFilepath : string * 
        outputFilepath : string * 
        overWrite : bool * 
        audioCodec : FFMPEGAudioCodec * 
        bitrate : FfmpegAudioBitrate * 
        ?preserveMetadata : bool * 
        ?threads : int 
(* Defaults:
        let _preserveMetadata = defaultArg preserveMetadata false
        let _threads = defaultArg threads 1
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>inputFilepath</dt><dd>Type: System.String<br />The source video filepath.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The target video filepath.</dd><dt>overWrite</dt><dd>Type: System.Boolean<br />A value indicating whether to overwrite the target filepath if already exists.</dd><dt>audioCodec</dt><dd>Type: <a href="T_DevCase_ThirdParty_Ffmpeg_FFMPEGAudioCodec">DevCase.ThirdParty.Ffmpeg.FFMPEGAudioCodec</a><br />The audio codec to use.</dd><dt>bitrate</dt><dd>Type: <a href="T_DevCase_ThirdParty_Ffmpeg_FfmpegAudioBitrate">DevCase.ThirdParty.Ffmpeg.FfmpegAudioBitrate</a><br />The audio bitrate.</dd><dt>preserveMetadata (Optional)</dt><dd>Type: System.Boolean<br />A value indicating whether to preserve the source video metadata in the target video.</dd><dt>threads (Optional)</dt><dd>Type: System.Int32<br />The amount of threads to use. 

 Default value is `1`.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg Namespace</a><br />