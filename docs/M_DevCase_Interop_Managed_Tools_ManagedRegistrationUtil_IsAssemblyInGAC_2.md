# ManagedRegistrationUtil.IsAssemblyInGAC Method (AssemblyName)
 

Determines whether the specified assembly is installed in GAC (Global Assembly Cache).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAssemblyInGAC(
	AssemblyName assemblyName
)
```

**VB**<br />
``` VB
Public Shared Function IsAssemblyInGAC ( 
	assemblyName As AssemblyName
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim assemblyName As AssemblyName
Dim returnValue As Boolean

returnValue = ManagedRegistrationUtil.IsAssemblyInGAC(assemblyName)
```

**C++**<br />
``` C++
public:
static bool IsAssemblyInGAC(
	AssemblyName^ assemblyName
)
```

**F#**<br />
``` F#
static member IsAssemblyInGAC : 
        assemblyName : AssemblyName -> bool 

```


#### Parameters
&nbsp;<dl><dt>assemblyName</dt><dd>Type: System.Reflection.AssemblyName<br />An AssemblyName instance that contains the assembly info.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the assembly is installed in GAC; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.ReflectionOnlyLoad("C:\Windows\Microsoft.NET\Framework64\v4.0.30319\System.dll")
Dim asmName As AssemblyName = asm.GetName()
Dim isAssemblyInstalled As Boolean = IsAssemblyInGAC(asmName)
Console.WriteLine(isAssemblyInstalled)
```


## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asmName As New AssemblyName()
With asmName
    .Name = "mscorlib"
    .Version = New Version("4.0.0.0")
    .ProcessorArchitecture = ProcessorArchitecture.Amd64
    .CultureInfo = New CultureInfo("") ' neutral
End With

Dim isAssemblyInstalled As Boolean = IsAssemblyInGAC(asmName)
Console.WriteLine(isAssemblyInstalled)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil">ManagedRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil_IsAssemblyInGAC">IsAssemblyInGAC Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />