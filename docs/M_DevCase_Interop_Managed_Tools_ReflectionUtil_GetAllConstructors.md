# ReflectionUtil.GetAllConstructors Method (Object, BindingFlags)
 

Gets all the constructors declared in the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<ConstructorInfo> GetAllConstructors(
	Object obj,
	BindingFlags bindingFlags = BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
)
```

**VB**<br />
``` VB
Public Shared Function GetAllConstructors ( 
	obj As Object,
	Optional bindingFlags As BindingFlags = BindingFlags.DeclaredOnly Or BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic
) As IEnumerable(Of ConstructorInfo)
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim bindingFlags As BindingFlags
Dim returnValue As IEnumerable(Of ConstructorInfo)

returnValue = ReflectionUtil.GetAllConstructors(obj, 
	bindingFlags)
```

**C++**<br />
``` C++
public:
static IEnumerable<ConstructorInfo^>^ GetAllConstructors(
	Object^ obj, 
	BindingFlags bindingFlags = BindingFlags::DeclaredOnly|BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic
)
```

**F#**<br />
``` F#
static member GetAllConstructors : 
        obj : Object * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
*)
-> IEnumerable<ConstructorInfo> 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the constructors.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: IEnumerable(ConstructorInfo)<br />A IEnumerable(T) collection with all the constructors found.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim constructors As IEnumerable(Of ConstructorInfo) = GetAllConstructors(Me)

For Each constructor As ConstructorInfo In constructors
    Console.WriteLine(constructor.Name)
Next constructor
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllConstructors">GetAllConstructors Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />