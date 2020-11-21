# ReflectionUtil.GetAllDerivedTypes(*T*) Method 
 

Gets all the types that inherits from the source Type within the Assembly in which the source Type is defined.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<Type> GetAllDerivedTypes<T>()

```

**VB**<br />
``` VB
Public Shared Function GetAllDerivedTypes(Of T) As IEnumerable(Of Type)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IEnumerable(Of Type)

returnValue = ReflectionUtil.GetAllDerivedTypes()
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<Type^>^ GetAllDerivedTypes()
```

**F#**<br />
``` F#
static member GetAllDerivedTypes : unit -> IEnumerable<Type> 

```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source Type.</dd></dl>

#### Return Value
Type: IEnumerable(Type)<br />All the types that inherits from the source Type within the loaded assembly in which the source Type is defined; or a null reference (`Nothing` in Visual Basic) if there is no Type that inherits from the source Type.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim derivedTypes As IEnumerable(Of Type) = GetAllDerivedTypes(Of Control)()

Console.WriteLine(String.Join(Environment.NewLine, derivedTypes))
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllDerivedTypes">GetAllDerivedTypes Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />