# ReflectionUtil.GetAllConstructors(*T*) Method (BindingFlags)
 

Gets all the constructors declared in the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<ConstructorInfo> GetAllConstructors<T>(
	BindingFlags bindingFlags = BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
)

```

**VB**<br />
``` VB
Public Shared Function GetAllConstructors(Of T) ( 
	Optional bindingFlags As BindingFlags = BindingFlags.DeclaredOnly Or BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic
) As IEnumerable(Of ConstructorInfo)
```

**VB Usage**<br />
``` VB Usage
Dim bindingFlags As BindingFlags
Dim returnValue As IEnumerable(Of ConstructorInfo)

returnValue = ReflectionUtil.GetAllConstructors(bindingFlags)
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<ConstructorInfo^>^ GetAllConstructors(
	BindingFlags bindingFlags = BindingFlags::DeclaredOnly|BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic
)
```

**F#**<br />
``` F#
static member GetAllConstructors : 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
*)
-> IEnumerable<ConstructorInfo> 

```


#### Parameters
&nbsp;<dl><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source type from which to retrieve its constructors.</dd></dl>

#### Return Value
Type: IEnumerable(ConstructorInfo)<br />A IEnumerable(T) collection with all the constructors found.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim constructors As IEnumerable(Of ConstructorInfo) = 
    GetAllConstructors(Of Form)()

For Each constructor As ConstructorInfo In constructors
    Console.WriteLine(constructor.Name)
Next constructor
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllConstructors">GetAllConstructors Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />