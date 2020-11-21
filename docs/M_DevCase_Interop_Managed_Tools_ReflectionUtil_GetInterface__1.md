# ReflectionUtil.GetInterface(*T*) Method (String)
 

Searches for the specified interface implemented or inherited in the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Type GetInterface<T>(
	string interfaceName
)

```

**VB**<br />
``` VB
Public Shared Function GetInterface(Of T) ( 
	interfaceName As String
) As Type
```

**VB Usage**<br />
``` VB Usage
Dim interfaceName As String
Dim returnValue As Type

returnValue = ReflectionUtil.GetInterface(interfaceName)
```

**C++**<br />
``` C++
public:
generic<typename T>
static Type^ GetInterface(
	String^ interfaceName
)
```

**F#**<br />
``` F#
static member GetInterface : 
        interfaceName : string -> Type 

```


#### Parameters
&nbsp;<dl><dt>interfaceName</dt><dd>Type: System.String<br />The name of the interface to search for.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source type from which to retrieve the interface.</dd></dl>

#### Return Value
Type: Type<br />The resulting interface implemented or inherited in the specified Type.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim [interface] As Type = GetInterface(Of Form)("IWin32Window")
Console.WriteLine([interface].FullName)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetInterface">GetInterface Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />