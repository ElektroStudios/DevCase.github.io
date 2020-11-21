# CompilerSettings.Verbose Property 
 

Gets or sets a value that instructs the compiler to produce verbose status and error messages.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Verbose { get; set; }
```

**VB**<br />
``` VB
Public Property Verbose As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
Dim value As Boolean

value = instance.Verbose

instance.Verbose = value
```

**C++**<br />
``` C++
public:
property bool Verbose {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member Verbose : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if verbose enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerSettings">CompilerSettings Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />