# MP3ValExitedEventArgs.FileIsFixed Property 
 

Gets a value indicating whether the source audio file was fixed. 

 This value is always `false` (`False` in Visual Basic) if not realizing a <a href="T_DevCase_ThirdParty_MP3Val_MP3ValTask">Fix</a> task.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val_Eventing">DevCase.ThirdParty.MP3Val.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool FileIsFixed { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property FileIsFixed As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3ValExitedEventArgs
Dim value As Boolean

value = instance.FileIsFixed

```

**C++**<br />
``` C++
public:
property bool FileIsFixed {
	bool get ();
}
```

**F#**<br />
``` F#
member FileIsFixed : bool with get

```


#### Property Value
Type: Boolean<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.MP3Val.Eventing.MP3ValExitedEventArgs.FileIsFixed"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs">MP3ValExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_MP3Val_Eventing">DevCase.ThirdParty.MP3Val.Eventing Namespace</a><br />