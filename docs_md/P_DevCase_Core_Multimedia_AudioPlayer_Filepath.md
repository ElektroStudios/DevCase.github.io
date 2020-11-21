# AudioPlayer.Filepath Property 
 

Gets the filepath of the audio file that will be played.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string Filepath { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Filepath As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim value As String

value = instance.Filepath

```

**C++**<br />
``` C++
public:
virtual property String^ Filepath {
	String^ get ();
}
```

**F#**<br />
``` F#
abstract Filepath : string with get
override Filepath : string with get
```


#### Property Value
Type: String<br />The filepath of the audio file that will be played.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Any file loaded.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />