# CompilerSettings.OutputLanguage Property 
 

Gets or sets the language that the compiler will use to display the output messages. 

 This option is only available for C# compiler.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CultureInfo OutputLanguage { get; set; }
```

**VB**<br />
``` VB
Public Property OutputLanguage As CultureInfo
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
Dim value As CultureInfo

value = instance.OutputLanguage

instance.OutputLanguage = value
```

**C++**<br />
``` C++
public:
property CultureInfo^ OutputLanguage {
	CultureInfo^ get ();
	void set (CultureInfo^ value);
}
```

**F#**<br />
``` F#
member OutputLanguage : CultureInfo with get, set

```


#### Property Value
Type: CultureInfo<br />The language that the compiler will use to display the output messages.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerSettings">CompilerSettings Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />