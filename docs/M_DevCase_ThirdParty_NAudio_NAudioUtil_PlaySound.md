# NAudioUtil.PlaySound Method (MemoryStream, Single)
 

Plays an audio from a MemoryStream.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_NAudio">DevCase.ThirdParty.NAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void PlaySound(
	MemoryStream stream,
	float volume = 0f
)
```

**VB**<br />
``` VB
Public Shared Sub PlaySound ( 
	stream As MemoryStream,
	Optional volume As Single = 0F
)
```

**VB Usage**<br />
``` VB Usage
Dim stream As MemoryStream
Dim volume As SingleNAudioUtil.PlaySound(stream, volume)
```

**C++**<br />
``` C++
public:
static void PlaySound(
	MemoryStream^ stream, 
	float volume = 0f
)
```

**F#**<br />
``` F#
static member PlaySound : 
        stream : MemoryStream * 
        ?volume : float32 
(* Defaults:
        let _volume = defaultArg volume 0f
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>stream</dt><dd>Type: System.IO.MemoryStream<br />\[Missing <param name="stream"/> documentation for "M:DevCase.ThirdParty.NAudio.NAudioUtil.PlaySound(System.IO.MemoryStream,System.Single)"\]</dd><dt>volume (Optional)</dt><dd>Type: System.Single<br />\[Missing <param name="volume"/> documentation for "M:DevCase.ThirdParty.NAudio.NAudioUtil.PlaySound(System.IO.MemoryStream,System.Single)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_NAudio_NAudioUtil">NAudioUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_NAudio_NAudioUtil_PlaySound">PlaySound Overload</a><br /><a href="N_DevCase_ThirdParty_NAudio">DevCase.ThirdParty.NAudio Namespace</a><br />