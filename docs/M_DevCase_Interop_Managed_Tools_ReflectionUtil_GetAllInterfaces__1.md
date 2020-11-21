# ReflectionUtil.GetAllInterfaces(*T*) Method 
 

Gets all the interfaces implemented or inherited by the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Type[] GetAllInterfaces<T>()

```

**VB**<br />
``` VB
Public Shared Function GetAllInterfaces(Of T) As Type()
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Type()

returnValue = ReflectionUtil.GetAllInterfaces()
```

**C++**<br />
``` C++
public:
generic<typename T>
static array<Type^>^ GetAllInterfaces()
```

**F#**<br />
``` F#
static member GetAllInterfaces : unit -> Type[] 

```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source type from which to retrieve the interfaces.</dd></dl>

#### Return Value
Type: Type[]<br />All the found interfaces implemented or inherited by the specified Type.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim interfaces As Type() = GetAllInterfaces(Of Form).OrderBy(Function(type As Type) type.FullName).ToArray()

For Each [interface] As Type In interfaces
    Console.WriteLine([interface].FullName)
Next [interface]
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllInterfaces">GetAllInterfaces Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />