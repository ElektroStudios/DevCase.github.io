# AudioPlayer.LoadFile Method 
 

Loads an audio file on the player.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void LoadFile(
	string filepath
)
```

**VB**<br />
``` VB
Public Overridable Sub LoadFile ( 
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim filepath As String

instance.LoadFile(filepath)
```

**C++**<br />
``` C++
public:
virtual void LoadFile(
	String^ filepath
)
```

**F#**<br />
``` F#
abstract LoadFile : 
        filepath : string -> unit 
override LoadFile : 
        filepath : string -> unit 
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The audio filepath.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File not found.</td></tr><tr><td>NotImplementedException</td><td>Audio format not supported.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />