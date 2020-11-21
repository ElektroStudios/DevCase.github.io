# ManagedRegistrationUtil.RegisterManagedAssembly Method (String, AssemblyRegistrationFlags)
 

Registers the classes in a managed .NET assembly to enable creation from COM. 

 This is the equivalent for calling `RegAsm.exe` to register a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool RegisterManagedAssembly(
	string filepath,
	AssemblyRegistrationFlags flags
)
```

**VB**<br />
``` VB
Public Shared Function RegisterManagedAssembly ( 
	filepath As String,
	flags As AssemblyRegistrationFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim flags As AssemblyRegistrationFlags
Dim returnValue As Boolean

returnValue = ManagedRegistrationUtil.RegisterManagedAssembly(filepath, 
	flags)
```

**C++**<br />
``` C++
public:
static bool RegisterManagedAssembly(
	String^ filepath, 
	AssemblyRegistrationFlags flags
)
```

**F#**<br />
``` F#
static member RegisterManagedAssembly : 
        filepath : string * 
        flags : AssemblyRegistrationFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path of the assembly to be registered.</dd><dt>flags</dt><dd>Type: System.Runtime.InteropServices.AssemblyRegistrationFlags<br />Defines a set of flags used when registering assemblies.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the assembly contains types that were successfully registered; otherwise `false` (`False` in Visual Basic) if the assembly contains no eligible types.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil">ManagedRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil_RegisterManagedAssembly">RegisterManagedAssembly Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />