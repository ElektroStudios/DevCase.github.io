# CompilerWorkDoneEventArgs.SourceFilePath Property 
 

Gets the source filepath. Only when a file is used to compile.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string SourceFilePath { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property SourceFilePath As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerWorkDoneEventArgs
Dim value As String

value = instance.SourceFilePath

```

**C++**<br />
``` C++
public:
property String^ SourceFilePath {
	String^ get ();
}
```

**F#**<br />
``` F#
member SourceFilePath : string with get

```


#### Property Value
Type: String<br />The source filepath. Only when a file is used to compile.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs">CompilerWorkDoneEventArgs Class</a><br /><a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing Namespace</a><br />