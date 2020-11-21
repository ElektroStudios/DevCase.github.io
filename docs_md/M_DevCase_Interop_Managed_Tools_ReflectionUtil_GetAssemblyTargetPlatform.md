# ReflectionUtil.GetAssemblyTargetPlatform Method 
 

Determines the target platform (i386, AMD64, etc) of a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ImageFileMachine GetAssemblyTargetPlatform(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetAssemblyTargetPlatform ( 
	filepath As String
) As ImageFileMachine
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As ImageFileMachine

returnValue = ReflectionUtil.GetAssemblyTargetPlatform(filepath)
```

**C++**<br />
``` C++
public:
static ImageFileMachine GetAssemblyTargetPlatform(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetAssemblyTargetPlatform : 
        filepath : string -> ImageFileMachine 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file to examine.</dd></dl>

#### Return Value
Type: ImageFileMachine<br />The target platform.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim targetPlatform As ImageFileMachine = GetAssemblyTargetPlatform("C:\Assembly.dll")
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />