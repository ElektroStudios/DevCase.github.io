# MP3ValStartedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValStartedEventArgs">MP3ValStartedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val_Eventing">DevCase.ThirdParty.MP3Val.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MP3ValStartedEventArgs(
	string arguments,
	string file,
	MP3ValTask task
)
```

**VB**<br />
``` VB
Public Sub New ( 
	arguments As String,
	file As String,
	task As MP3ValTask
)
```

**VB Usage**<br />
``` VB Usage
Dim arguments As String
Dim file As String
Dim task As MP3ValTask

Dim instance As New MP3ValStartedEventArgs(arguments, 
	file, task)
```

**C++**<br />
``` C++
public:
MP3ValStartedEventArgs(
	String^ arguments, 
	String^ file, 
	MP3ValTask task
)
```

**F#**<br />
``` F#
new : 
        arguments : string * 
        file : string * 
        task : MP3ValTask -> MP3ValStartedEventArgs
```


#### Parameters
&nbsp;<dl><dt>arguments</dt><dd>Type: System.String<br />The arguments that was passed to the process.</dd><dt>file</dt><dd>Type: System.String<br />The source audio filepath that was passed to the process.</dd><dt>task</dt><dd>Type: <a href="T_DevCase_ThirdParty_MP3Val_MP3ValTask">DevCase.ThirdParty.MP3Val.MP3ValTask</a><br />The MP3Val task that is being realized.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValStartedEventArgs">MP3ValStartedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_MP3Val_Eventing">DevCase.ThirdParty.MP3Val.Eventing Namespace</a><br />