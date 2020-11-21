# ReflectionUtil.GetInterface Method (Object, String)
 

Searches for the specified interface implemented or inherited in the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Type GetInterface(
	Object obj,
	string interfaceName
)
```

**VB**<br />
``` VB
Public Shared Function GetInterface ( 
	obj As Object,
	interfaceName As String
) As Type
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim interfaceName As String
Dim returnValue As Type

returnValue = ReflectionUtil.GetInterface(obj, 
	interfaceName)
```

**C++**<br />
``` C++
public:
static Type^ GetInterface(
	Object^ obj, 
	String^ interfaceName
)
```

**F#**<br />
``` F#
static member GetInterface : 
        obj : Object * 
        interfaceName : string -> Type 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the interface.</dd><dt>interfaceName</dt><dd>Type: System.String<br />The name of the interface to search for.</dd></dl>

#### Return Value
Type: Type<br />The resulting interface implemented or inherited in the specified object.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim [interface] As Type = GetInterface(Me, "IWin32Window")
Console.WriteLine([interface].FullName)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetInterface">GetInterface Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />