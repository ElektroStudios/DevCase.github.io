# CompilerResultsEx.Errors Property 
 

Gets the compiler errors.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CompilerErrorEx[] Errors { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Errors As CompilerErrorEx()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerResultsEx
Dim value As CompilerErrorEx()

value = instance.Errors

```

**C++**<br />
``` C++
public:
property array<CompilerErrorEx^>^ Errors {
	array<CompilerErrorEx^>^ get ();
}
```

**F#**<br />
``` F#
member Errors : CompilerErrorEx[] with get

```


#### Property Value
Type: <a href="T_DevCase_Interop_Managed_CompilerErrorEx">CompilerErrorEx</a>[]<br />The compiler errors.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerResultsEx">CompilerResultsEx Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />