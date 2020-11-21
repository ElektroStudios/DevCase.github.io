# CompilerSettings.Platform Property 
 

Gets or sets a value that specifies which platform version of common language runtime (CLR) can run the output file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public AssemblyPlatform Platform { get; set; }
```

**VB**<br />
``` VB
Public Property Platform As AssemblyPlatform
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
Dim value As AssemblyPlatform

value = instance.Platform

instance.Platform = value
```

**C++**<br />
``` C++
public:
property AssemblyPlatform Platform {
	AssemblyPlatform get ();
	void set (AssemblyPlatform value);
}
```

**F#**<br />
``` F#
member Platform : AssemblyPlatform with get, set

```


#### Property Value
Type: <a href="T_DevCase_Interop_Managed_AssemblyPlatform">AssemblyPlatform</a><br />The platform version of common language runtime (CLR) which can run the output file.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerSettings">CompilerSettings Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />