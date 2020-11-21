# ManagedRegistrationUtil.UnregisterManagedAssembly Method (String)
 

Unregisters the classes in a managed .NET assembly. 

 This is the equivalent for calling `RegAsm.exe` to unregister a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool UnregisterManagedAssembly(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function UnregisterManagedAssembly ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Boolean

returnValue = ManagedRegistrationUtil.UnregisterManagedAssembly(filepath)
```

**C++**<br />
``` C++
public:
static bool UnregisterManagedAssembly(
	String^ filepath
)
```

**F#**<br />
``` F#
static member UnregisterManagedAssembly : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path of the assembly to be unregistered.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the assembly contains types that were successfully unregistered; otherwise `false` (`False` in Visual Basic) if the assembly contains no eligible types.

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil">ManagedRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil_UnregisterManagedAssembly">UnregisterManagedAssembly Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />