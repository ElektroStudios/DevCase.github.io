# AudioPlayer.Channels Property 
 

Gets the channels of the current audio file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual int Channels { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Channels As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim value As Integer

value = instance.Channels

```

**C++**<br />
``` C++
public:
virtual property int Channels {
	int get ();
}
```

**F#**<br />
``` F#
abstract Channels : int with get
override Channels : int with get
```


#### Property Value
Type: Int32<br />The channels of the current audio file.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Any file loaded.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />