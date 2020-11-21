# ManagedRegistrationUtil.UnregisterManagedAssembly Method (FileInfo)
 

Unregisters the classes in a managed .NET assembly. 

 This is the equivalent for calling `RegAsm.exe` to unregister a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool UnregisterManagedAssembly(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function UnregisterManagedAssembly ( 
	file As FileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As Boolean

returnValue = ManagedRegistrationUtil.UnregisterManagedAssembly(file)
```

**C++**<br />
``` C++
public:
static bool UnregisterManagedAssembly(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member UnregisterManagedAssembly : 
        file : FileInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The assembly to be unregistered.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the assembly contains types that were successfully unregistered; otherwise `false` (`False` in Visual Basic) if the assembly contains no eligible types.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil">ManagedRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil_UnregisterManagedAssembly">UnregisterManagedAssembly Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />