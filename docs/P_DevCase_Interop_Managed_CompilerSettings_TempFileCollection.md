# CompilerSettings.TempFileCollection Property 
 

Gets or sets the temporary files collection where the compiler stores the temporary files generated during a build.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TempFileCollection TempFileCollection { get; set; }
```

**VB**<br />
``` VB
Public Property TempFileCollection As TempFileCollection
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
Dim value As TempFileCollection

value = instance.TempFileCollection

instance.TempFileCollection = value
```

**C++**<br />
``` C++
public:
property TempFileCollection^ TempFileCollection {
	TempFileCollection^ get ();
	void set (TempFileCollection^ value);
}
```

**F#**<br />
``` F#
member TempFileCollection : TempFileCollection with get, set

```


#### Property Value
Type: TempFileCollection<br />The temporary files collection where the compiler stores the temporary files generated during a build.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerSettings">CompilerSettings Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />