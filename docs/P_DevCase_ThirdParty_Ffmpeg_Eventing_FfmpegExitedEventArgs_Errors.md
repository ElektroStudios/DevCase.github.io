# FfmpegExitedEventArgs.Errors Property 
 

Gets the error messages of the finished task (if any).

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public List<string> Errors { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Errors As List(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FfmpegExitedEventArgs
Dim value As List(Of String)

value = instance.Errors

```

**C++**<br />
``` C++
public:
property List<String^>^ Errors {
	List<String^>^ get ();
}
```

**F#**<br />
``` F#
member Errors : List<string> with get

```


#### Property Value
Type: List(String)<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.Ffmpeg.Eventing.FfmpegExitedEventArgs.Errors"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegExitedEventArgs">FfmpegExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing Namespace</a><br />