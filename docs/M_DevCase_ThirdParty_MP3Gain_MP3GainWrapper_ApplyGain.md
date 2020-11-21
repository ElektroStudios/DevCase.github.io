# MP3GainWrapper.ApplyGain Method (FileInfo, Int32, Boolean)
 

Applies a volume gain change on the specified audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ApplyGain(
	FileInfo file,
	int gainLevel,
	bool preserveDatestamp = true
)
```

**VB**<br />
``` VB
Public Function ApplyGain ( 
	file As FileInfo,
	gainLevel As Integer,
	Optional preserveDatestamp As Boolean = true
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainWrapper
Dim file As FileInfo
Dim gainLevel As Integer
Dim preserveDatestamp As Boolean
Dim returnValue As Integer

returnValue = instance.ApplyGain(file, 
	gainLevel, preserveDatestamp)
```

**C++**<br />
``` C++
public:
int ApplyGain(
	FileInfo^ file, 
	int gainLevel, 
	bool preserveDatestamp = true
)
```

**F#**<br />
``` F#
member ApplyGain : 
        file : FileInfo * 
        gainLevel : int * 
        ?preserveDatestamp : bool 
(* Defaults:
        let _preserveDatestamp = defaultArg preserveDatestamp true
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The audio file.</dd><dt>gainLevel</dt><dd>Type: System.Int32<br />The volume gain change, in decibels.</dd><dt>preserveDatestamp (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the file date is untouched after successful task.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>gainLevel;Value from range -100 to +100 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_MP3GainWrapper">MP3GainWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_MP3Gain_MP3GainWrapper_ApplyGain">ApplyGain Overload</a><br /><a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain Namespace</a><br />