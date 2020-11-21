# AudioPlayer.Seek Method (Int64)
 

Sets the playback position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Seek(
	long milliseconds
)
```

**VB**<br />
``` VB
Public Overridable Sub Seek ( 
	milliseconds As Long
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim milliseconds As Long

instance.Seek(milliseconds)
```

**C++**<br />
``` C++
public:
virtual void Seek(
	long long milliseconds
)
```

**F#**<br />
``` F#
abstract Seek : 
        milliseconds : int64 -> unit 
override Seek : 
        milliseconds : int64 -> unit 
```


#### Parameters
&nbsp;<dl><dt>milliseconds</dt><dd>Type: System.Int64<br />The amount of milliseconds to seek.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Cannot pause playback because the player is not playing any audio.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="Overload_DevCase_Core_Multimedia_AudioPlayer_Seek">Seek Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />