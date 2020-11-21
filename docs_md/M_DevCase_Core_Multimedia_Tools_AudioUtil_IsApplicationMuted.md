# AudioUtil.IsApplicationMuted Method 
 

Gets a value that determine whether the audio volume of the specified application is muted.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsApplicationMuted(
	Process pr
)
```

**VB**<br />
``` VB
Public Shared Function IsApplicationMuted ( 
	pr As Process
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim returnValue As Boolean

returnValue = AudioUtil.IsApplicationMuted(pr)
```

**C++**<br />
``` C++
public:
static bool IsApplicationMuted(
	Process^ pr
)
```

**F#**<br />
``` F#
static member IsApplicationMuted : 
        pr : Process -> bool 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The Process.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the application is muted, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Tools_AudioUtil">AudioUtil Class</a><br /><a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools Namespace</a><br />