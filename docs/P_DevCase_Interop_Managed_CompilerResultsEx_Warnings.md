# CompilerResultsEx.Warnings Property 
 

Gets the compiler warnings.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CompilerWarning[] Warnings { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Warnings As CompilerWarning()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerResultsEx
Dim value As CompilerWarning()

value = instance.Warnings

```

**C++**<br />
``` C++
public:
property array<CompilerWarning^>^ Warnings {
	array<CompilerWarning^>^ get ();
}
```

**F#**<br />
``` F#
member Warnings : CompilerWarning[] with get

```


#### Property Value
Type: <a href="T_DevCase_Interop_Managed_CompilerWarning">CompilerWarning</a>[]<br />The compiler warnings.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerResultsEx">CompilerResultsEx Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />