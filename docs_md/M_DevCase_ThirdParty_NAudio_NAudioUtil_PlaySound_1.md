# NAudioUtil.PlaySound Method (String, Single)
 

Plays an audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_NAudio">DevCase.ThirdParty.NAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void PlaySound(
	string file,
	float volume = 0f
)
```

**VB**<br />
``` VB
Public Shared Sub PlaySound ( 
	file As String,
	Optional volume As Single = 0F
)
```

**VB Usage**<br />
``` VB Usage
Dim file As String
Dim volume As SingleNAudioUtil.PlaySound(file, volume)
```

**C++**<br />
``` C++
public:
static void PlaySound(
	String^ file, 
	float volume = 0f
)
```

**F#**<br />
``` F#
static member PlaySound : 
        file : string * 
        ?volume : float32 
(* Defaults:
        let _volume = defaultArg volume 0f
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />\[Missing <param name="file"/> documentation for "M:DevCase.ThirdParty.NAudio.NAudioUtil.PlaySound(System.String,System.Single)"\]</dd><dt>volume (Optional)</dt><dd>Type: System.Single<br />\[Missing <param name="volume"/> documentation for "M:DevCase.ThirdParty.NAudio.NAudioUtil.PlaySound(System.String,System.Single)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_NAudio_NAudioUtil">NAudioUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_NAudio_NAudioUtil_PlaySound">PlaySound Overload</a><br /><a href="N_DevCase_ThirdParty_NAudio">DevCase.ThirdParty.NAudio Namespace</a><br />