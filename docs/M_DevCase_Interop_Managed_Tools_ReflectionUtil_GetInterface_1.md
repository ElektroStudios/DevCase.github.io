# ReflectionUtil.GetInterface Method (Type, String)
 

Searches for the specified interface implemented or inherited in the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Type GetInterface(
	Type type,
	string interfaceName
)
```

**VB**<br />
``` VB
Public Shared Function GetInterface ( 
	type As Type,
	interfaceName As String
) As Type
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim interfaceName As String
Dim returnValue As Type

returnValue = ReflectionUtil.GetInterface(type, 
	interfaceName)
```

**C++**<br />
``` C++
public:
static Type^ GetInterface(
	Type^ type, 
	String^ interfaceName
)
```

**F#**<br />
``` F#
static member GetInterface : 
        type : Type * 
        interfaceName : string -> Type 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />The source Type from which to retrieve the interface.</dd><dt>interfaceName</dt><dd>Type: System.String<br />The name of the interface to search for.</dd></dl>

#### Return Value
Type: Type<br />The resulting interface implemented or inherited in the specified Type.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim [interface] As Type = GetInterface(GetType(Form), "IWin32Window")
Console.WriteLine([interface].FullName)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetInterface">GetInterface Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />