# CompilerSettings.SubsystemVersion Property 
 

Gets or sets a value that specifies the minimum version of the subsystem on which the generated executable file can run, thereby determining the versions of Windows on which the executable file can run. Most commonly, this option ensures that the executable file can leverage particular security features that aren’t available with older versions of Windows.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string SubsystemVersion { get; set; }
```

**VB**<br />
``` VB
Public Property SubsystemVersion As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
Dim value As String

value = instance.SubsystemVersion

instance.SubsystemVersion = value
```

**C++**<br />
``` C++
public:
property String^ SubsystemVersion {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member SubsystemVersion : string with get, set

```


#### Property Value
Type: String<br />The subsystem on which the generated executable file can run.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerSettings">CompilerSettings Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />