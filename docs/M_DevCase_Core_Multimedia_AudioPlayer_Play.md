# AudioPlayer.Play Method 
 

Plays the file that is specified as the filename.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Play(
	AudioPlayMode playbackMode = AudioPlayMode.Background
)
```

**VB**<br />
``` VB
Public Overridable Sub Play ( 
	Optional playbackMode As AudioPlayMode = AudioPlayMode.Background
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim playbackMode As AudioPlayMode

instance.Play(playbackMode)
```

**C++**<br />
``` C++
public:
virtual void Play(
	AudioPlayMode playbackMode = AudioPlayMode::Background
)
```

**F#**<br />
``` F#
abstract Play : 
        ?playbackMode : AudioPlayMode 
(* Defaults:
        let _playbackMode = defaultArg playbackMode AudioPlayMode.Background
*)
-> unit 
override Play : 
        ?playbackMode : AudioPlayMode 
(* Defaults:
        let _playbackMode = defaultArg playbackMode AudioPlayMode.Background
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>playbackMode (Optional)</dt><dd>Type: Microsoft.VisualBasic.AudioPlayMode<br />The playback mode.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>playbackMode</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />