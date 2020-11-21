# ReflectionUtil.GetAssemblyPEKind Method 
 

Determines the PE (Portable Executable) type of a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PortableExecutableKinds GetAssemblyPEKind(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetAssemblyPEKind ( 
	filepath As String
) As PortableExecutableKinds
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As PortableExecutableKinds

returnValue = ReflectionUtil.GetAssemblyPEKind(filepath)
```

**C++**<br />
``` C++
public:
static PortableExecutableKinds GetAssemblyPEKind(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetAssemblyPEKind : 
        filepath : string -> PortableExecutableKinds 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file to examine.</dd></dl>

#### Return Value
Type: PortableExecutableKinds<br />The PE type.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim peKind As PortableExecutableKinds = GetAssemblyPEKind("C:\Assembly.dll")
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />