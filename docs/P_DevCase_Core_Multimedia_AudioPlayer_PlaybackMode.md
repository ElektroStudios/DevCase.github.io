# AudioPlayer.PlaybackMode Property 
 

Gets or sets the playback mode for the current audio file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual AudioPlayMode PlaybackMode { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property PlaybackMode As AudioPlayMode
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim value As AudioPlayMode

value = instance.PlaybackMode

instance.PlaybackMode = value
```

**C++**<br />
``` C++
public:
virtual property AudioPlayMode PlaybackMode {
	AudioPlayMode get ();
	void set (AudioPlayMode value);
}
```

**F#**<br />
``` F#
abstract PlaybackMode : AudioPlayMode with get, set
override PlaybackMode : AudioPlayMode with get, set
```


#### Property Value
Type: AudioPlayMode<br />The playback mode for the current audio file.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />