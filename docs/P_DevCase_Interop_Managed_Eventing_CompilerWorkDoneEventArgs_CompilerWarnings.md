# CompilerWorkDoneEventArgs.CompilerWarnings Property 
 

Gets the compiler warnings.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<CompilerWarning> CompilerWarnings { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property CompilerWarnings As IEnumerable(Of CompilerWarning)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerWorkDoneEventArgs
Dim value As IEnumerable(Of CompilerWarning)

value = instance.CompilerWarnings

```

**C++**<br />
``` C++
public:
property IEnumerable<CompilerWarning^>^ CompilerWarnings {
	IEnumerable<CompilerWarning^>^ get ();
}
```

**F#**<br />
``` F#
member CompilerWarnings : IEnumerable<CompilerWarning> with get

```


#### Property Value
Type: IEnumerable(<a href="T_DevCase_Interop_Managed_CompilerWarning">CompilerWarning</a>)<br />The compiler warnings.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs">CompilerWorkDoneEventArgs Class</a><br /><a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing Namespace</a><br />