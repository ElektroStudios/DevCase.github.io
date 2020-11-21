# NAudioUtil.SetVolume Method 
 

Sets the volume of a WaveStream.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_NAudio">DevCase.ThirdParty.NAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static WaveOut SetVolume(
	WaveStream waveStream,
	float volume
)
```

**VB**<br />
``` VB
Public Shared Function SetVolume ( 
	waveStream As WaveStream,
	volume As Single
) As WaveOut
```

**VB Usage**<br />
``` VB Usage
Dim waveStream As WaveStream
Dim volume As Single
Dim returnValue As WaveOut

returnValue = NAudioUtil.SetVolume(waveStream, 
	volume)
```

**C++**<br />
``` C++
public:
static WaveOut^ SetVolume(
	WaveStream^ waveStream, 
	float volume
)
```

**F#**<br />
``` F#
static member SetVolume : 
        waveStream : WaveStream * 
        volume : float32 -> WaveOut 

```


#### Parameters
&nbsp;<dl><dt>waveStream</dt><dd>Type: WaveStream<br />\[Missing <param name="waveStream"/> documentation for "M:DevCase.ThirdParty.NAudio.NAudioUtil.SetVolume(NAudio.Wave.WaveStream,System.Single)"\]</dd><dt>volume</dt><dd>Type: System.Single<br />\[Missing <param name="volume"/> documentation for "M:DevCase.ThirdParty.NAudio.NAudioUtil.SetVolume(NAudio.Wave.WaveStream,System.Single)"\]</dd></dl>

#### Return Value
Type: WaveOut<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.NAudio.NAudioUtil.SetVolume(NAudio.Wave.WaveStream,System.Single)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_NAudio_NAudioUtil">NAudioUtil Class</a><br /><a href="N_DevCase_ThirdParty_NAudio">DevCase.ThirdParty.NAudio Namespace</a><br />