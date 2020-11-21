# ManagedRegistrationUtil.IsAssemblyInGAC Method (Assembly)
 

Determines whether the specified assembly is installed in GAC (Global Assembly Cache).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAssemblyInGAC(
	Assembly assembly
)
```

**VB**<br />
``` VB
Public Shared Function IsAssemblyInGAC ( 
	assembly As Assembly
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim assembly As [Assembly]
Dim returnValue As Boolean

returnValue = ManagedRegistrationUtil.IsAssemblyInGAC(assembly)
```

**C++**<br />
``` C++
public:
static bool IsAssemblyInGAC(
	Assembly^ assembly
)
```

**F#**<br />
``` F#
static member IsAssemblyInGAC : 
        assembly : Assembly -> bool 

```


#### Parameters
&nbsp;<dl><dt>assembly</dt><dd>Type: System.Reflection.Assembly<br />The source Assembly.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the assembly is installed in GAC; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.ReflectionOnlyLoadFrom("C:\Windows\Microsoft.NET\Framework64\v4.0.30319\System.dll")
Dim isAssemblyInstalled As Boolean = IsAssemblyInGAC(asm)
Console.WriteLine(isAssemblyInstalled)
```


## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assembly As Assembly = Assembly.GetExecutingAssembly()
Dim isAssemblyInstalled As Boolean = IsAssemblyInGAC(assembly)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil">ManagedRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil_IsAssemblyInGAC">IsAssemblyInGAC Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />