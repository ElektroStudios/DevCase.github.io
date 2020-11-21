# ReflectionUtil.GetAllDerivedTypes(*T*) Method (Assembly)
 

Gets all the types that inherits from the source Type within the specified Assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<Type> GetAllDerivedTypes<T>(
	Assembly assembly
)

```

**VB**<br />
``` VB
Public Shared Function GetAllDerivedTypes(Of T) ( 
	assembly As Assembly
) As IEnumerable(Of Type)
```

**VB Usage**<br />
``` VB Usage
Dim assembly As [Assembly]
Dim returnValue As IEnumerable(Of Type)

returnValue = ReflectionUtil.GetAllDerivedTypes(assembly)
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<Type^>^ GetAllDerivedTypes(
	Assembly^ assembly
)
```

**F#**<br />
``` F#
static member GetAllDerivedTypes : 
        assembly : Assembly -> IEnumerable<Type> 

```


#### Parameters
&nbsp;<dl><dt>assembly</dt><dd>Type: System.Reflection.Assembly<br />The assembly from wich to search for derived types.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source Type.</dd></dl>

#### Return Value
Type: IEnumerable(Type)<br />All the types that inherits from the source Type within the specified assembly; or a null reference (`Nothing` in Visual Basic) if there is no Type that inherits from the source Type.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim derivedTypes As IEnumerable(Of Type) = GetAllDerivedTypes(Of Control)(Assembly.GetExecutingAssembly())

Console.WriteLine(String.Join(Environment.NewLine, derivedTypes))
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllDerivedTypes">GetAllDerivedTypes Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />