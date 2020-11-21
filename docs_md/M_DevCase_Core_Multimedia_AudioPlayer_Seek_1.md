# AudioPlayer.Seek Method (TimeSpan)
 

Pauses the current playback.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Seek(
	TimeSpan position
)
```

**VB**<br />
``` VB
Public Overridable Sub Seek ( 
	position As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim position As TimeSpan

instance.Seek(position)
```

**C++**<br />
``` C++
public:
virtual void Seek(
	TimeSpan position
)
```

**F#**<br />
``` F#
abstract Seek : 
        position : TimeSpan -> unit 
override Seek : 
        position : TimeSpan -> unit 
```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.TimeSpan<br />The amount of time to seek.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Cannot pause playback because the player is not playing any audio.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="Overload_DevCase_Core_Multimedia_AudioPlayer_Seek">Seek Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />