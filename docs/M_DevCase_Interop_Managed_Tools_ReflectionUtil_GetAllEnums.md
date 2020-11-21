# ReflectionUtil.GetAllEnums Method 
 

Gets all the Enum types defined in the source Assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<Type> GetAllEnums(
	Assembly assembly
)
```

**VB**<br />
``` VB
Public Shared Function GetAllEnums ( 
	assembly As Assembly
) As IEnumerable(Of Type)
```

**VB Usage**<br />
``` VB Usage
Dim assembly As [Assembly]
Dim returnValue As IEnumerable(Of Type)

returnValue = ReflectionUtil.GetAllEnums(assembly)
```

**C++**<br />
``` C++
public:
static IEnumerable<Type^>^ GetAllEnums(
	Assembly^ assembly
)
```

**F#**<br />
``` F#
static member GetAllEnums : 
        assembly : Assembly -> IEnumerable<Type> 

```


#### Parameters
&nbsp;<dl><dt>assembly</dt><dd>Type: System.Reflection.Assembly<br />The source Assembly.</dd></dl>

#### Return Value
Type: IEnumerable(Type)<br />Returns all the Enum types defined in the source Assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assembly As Assembly = Assembly.GetExecutingAssembly()
Dim enums As IEnumerable(Of Type) = GetAllEnums(assembly)
For Each enu As Type In enums
    Console.WriteLine(String.Format("Name: {0}; Values: {1}", enu.FullName,
                                    String.Join(", ", [Enum].GetNames(enu))))
Next
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />