# ManagedRegistrationUtil.IsAssemblyInGAC Method (String)
 

Determines whether the specified assembly is installed in GAC (Global Assembly Cache).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAssemblyInGAC(
	string assemblyName
)
```

**VB**<br />
``` VB
Public Shared Function IsAssemblyInGAC ( 
	assemblyName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim assemblyName As String
Dim returnValue As Boolean

returnValue = ManagedRegistrationUtil.IsAssemblyInGAC(assemblyName)
```

**C++**<br />
``` C++
public:
static bool IsAssemblyInGAC(
	String^ assemblyName
)
```

**F#**<br />
``` F#
static member IsAssemblyInGAC : 
        assemblyName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>assemblyName</dt><dd>Type: System.String<br />A partial or full qualified GAC assembly name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the assembly is installed in GAC; otherwise, `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>assemblyName</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isAssemblyInstalled As Boolean = IsAssemblyInGAC("System.dll")
Dim isAssemblyInstalled As Boolean = IsAssemblyInGAC("mscorlib, Version=4.0.0.0, Culture=neutral, ProcessorArchitecture=AMD64")
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil">ManagedRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil_IsAssemblyInGAC">IsAssemblyInGAC Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />