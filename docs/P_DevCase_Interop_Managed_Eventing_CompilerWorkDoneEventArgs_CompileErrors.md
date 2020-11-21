# CompilerWorkDoneEventArgs.CompileErrors Property 
 

Gets the compiler errors.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<CompilerError> CompileErrors { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property CompileErrors As IEnumerable(Of CompilerError)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerWorkDoneEventArgs
Dim value As IEnumerable(Of CompilerError)

value = instance.CompileErrors

```

**C++**<br />
``` C++
public:
property IEnumerable<CompilerError^>^ CompileErrors {
	IEnumerable<CompilerError^>^ get ();
}
```

**F#**<br />
``` F#
member CompileErrors : IEnumerable<CompilerError> with get

```


#### Property Value
Type: IEnumerable(CompilerError)<br />The compiler errors.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs">CompilerWorkDoneEventArgs Class</a><br /><a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing Namespace</a><br />