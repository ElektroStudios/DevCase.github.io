# ManagedRegistrationUtil.IsAssemblyInGAC Method (FileInfo)
 

Determines whether the specified assembly is installed in GAC (Global Assembly Cache).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAssemblyInGAC(
	FileInfo assemblyFile
)
```

**VB**<br />
``` VB
Public Shared Function IsAssemblyInGAC ( 
	assemblyFile As FileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim assemblyFile As FileInfo
Dim returnValue As Boolean

returnValue = ManagedRegistrationUtil.IsAssemblyInGAC(assemblyFile)
```

**C++**<br />
``` C++
public:
static bool IsAssemblyInGAC(
	FileInfo^ assemblyFile
)
```

**F#**<br />
``` F#
static member IsAssemblyInGAC : 
        assemblyFile : FileInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>assemblyFile</dt><dd>Type: System.IO.FileInfo<br />The assembly file.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the assembly is installed in GAC; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isAssemblyInstalled As Boolean = IsAssemblyInGAC(New FileInfo("C:\Assembly.dll"))
Console.WriteLine(isAssemblyInstalled)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil">ManagedRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ManagedRegistrationUtil_IsAssemblyInGAC">IsAssemblyInGAC Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />