# WaveRecorder.Save Method 
 

Stops recording and saves the recorded audio to disk.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Save(
	string filepath,
	bool overWrite = false
)
```

**VB**<br />
``` VB
Public Overridable Sub Save ( 
	filepath As String,
	Optional overWrite As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As WaveRecorder
Dim filepath As String
Dim overWrite As Boolean

instance.Save(filepath, overWrite)
```

**C++**<br />
``` C++
public:
virtual void Save(
	String^ filepath, 
	bool overWrite = false
)
```

**F#**<br />
``` F#
abstract Save : 
        filepath : string * 
        ?overWrite : bool 
(* Defaults:
        let _overWrite = defaultArg overWrite false
*)
-> unit 
override Save : 
        filepath : string * 
        ?overWrite : bool 
(* Defaults:
        let _overWrite = defaultArg overWrite false
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd><dt>overWrite (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), overwrites any existing file.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Cannot save because any audio is recorded. or The destination file already exists.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_WaveRecorder">WaveRecorder Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />