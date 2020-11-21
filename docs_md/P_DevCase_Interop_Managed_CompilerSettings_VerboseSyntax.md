# CompilerSettings.VerboseSyntax Property 
 

Gets or sets a value that instructs the compiler from displaying code for syntax-related errors and warnings.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool VerboseSyntax { get; set; }
```

**VB**<br />
``` VB
Public Property VerboseSyntax As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
Dim value As Boolean

value = instance.VerboseSyntax

instance.VerboseSyntax = value
```

**C++**<br />
``` C++
public:
property bool VerboseSyntax {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member VerboseSyntax : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if syntax-verbose enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerSettings">CompilerSettings Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />