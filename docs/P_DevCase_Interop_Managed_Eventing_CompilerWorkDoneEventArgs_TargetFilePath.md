# CompilerWorkDoneEventArgs.TargetFilePath Property 
 

Gets the target .NET assembly filepath.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string TargetFilePath { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property TargetFilePath As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerWorkDoneEventArgs
Dim value As String

value = instance.TargetFilePath

```

**C++**<br />
``` C++
public:
property String^ TargetFilePath {
	String^ get ();
}
```

**F#**<br />
``` F#
member TargetFilePath : string with get

```


#### Property Value
Type: String<br />The target .NET assembly filepath.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs">CompilerWorkDoneEventArgs Class</a><br /><a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing Namespace</a><br />