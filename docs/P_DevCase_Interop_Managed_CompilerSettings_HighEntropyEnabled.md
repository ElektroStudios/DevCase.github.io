# CompilerSettings.HighEntropyEnabled Property 
 

Gets or sets a value that indicates whether a 64-bit executable or an executable that's marked by the <a href="T_DevCase_Interop_Managed_AssemblyPlatform">AnyCpu</a> compiler option supports high entropy Address Space Layout Randomization (ASLR).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool HighEntropyEnabled { get; set; }
```

**VB**<br />
``` VB
Public Property HighEntropyEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
Dim value As Boolean

value = instance.HighEntropyEnabled

instance.HighEntropyEnabled = value
```

**C++**<br />
``` C++
public:
property bool HighEntropyEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member HighEntropyEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if high entropy is enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerSettings">CompilerSettings Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />