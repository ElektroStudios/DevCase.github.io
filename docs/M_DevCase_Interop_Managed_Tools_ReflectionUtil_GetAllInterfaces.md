# ReflectionUtil.GetAllInterfaces Method (Object)
 

Gets all the interfaces implemented or inherited by the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Type[] GetAllInterfaces(
	Object obj
)
```

**VB**<br />
``` VB
Public Shared Function GetAllInterfaces ( 
	obj As Object
) As Type()
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim returnValue As Type()

returnValue = ReflectionUtil.GetAllInterfaces(obj)
```

**C++**<br />
``` C++
public:
static array<Type^>^ GetAllInterfaces(
	Object^ obj
)
```

**F#**<br />
``` F#
static member GetAllInterfaces : 
        obj : Object -> Type[] 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the interfaces.</dd></dl>

#### Return Value
Type: Type[]<br />All the found interfaces implemented or inherited by the specified object.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim interfaces As Type() = GetAllInterfaces(Me).OrderBy(Function(type As Type) type.FullName).ToArray()

For Each [interface] As Type In interfaces
    Console.WriteLine([interface].FullName)
Next [interface]
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllInterfaces">GetAllInterfaces Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />