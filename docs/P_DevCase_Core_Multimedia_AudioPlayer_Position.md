# AudioPlayer.Position Property 
 

Gets the audio position of the current playback, in milleseconds.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual TimeSpan Position { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Position As TimeSpan
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim value As TimeSpan

value = instance.Position

```

**C++**<br />
``` C++
public:
virtual property TimeSpan Position {
	TimeSpan get ();
}
```

**F#**<br />
``` F#
abstract Position : TimeSpan with get
override Position : TimeSpan with get
```


#### Property Value
Type: TimeSpan<br />The audio position of the current playback, in milleseconds.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Any file loaded.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />