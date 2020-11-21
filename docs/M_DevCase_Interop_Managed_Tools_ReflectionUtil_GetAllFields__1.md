# ReflectionUtil.GetAllFields(*T*) Method (Boolean, BindingFlags)
 

Gets all the fields declared in the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<FieldInfo> GetAllFields<T>(
	bool includeBaseTypes,
	BindingFlags bindingFlags = BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
)

```

**VB**<br />
``` VB
Public Shared Function GetAllFields(Of T) ( 
	includeBaseTypes As Boolean,
	Optional bindingFlags As BindingFlags = BindingFlags.DeclaredOnly Or BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic
) As IEnumerable(Of FieldInfo)
```

**VB Usage**<br />
``` VB Usage
Dim includeBaseTypes As Boolean
Dim bindingFlags As BindingFlags
Dim returnValue As IEnumerable(Of FieldInfo)

returnValue = ReflectionUtil.GetAllFields(includeBaseTypes, 
	bindingFlags)
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<FieldInfo^>^ GetAllFields(
	bool includeBaseTypes, 
	BindingFlags bindingFlags = BindingFlags::DeclaredOnly|BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic
)
```

**F#**<br />
``` F#
static member GetAllFields : 
        includeBaseTypes : bool * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
*)
-> IEnumerable<FieldInfo> 

```


#### Parameters
&nbsp;<dl><dt>includeBaseTypes</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), the search include fields declared in base types too.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source type from which to retrieve its fields.</dd></dl>

#### Return Value
Type: IEnumerable(FieldInfo)<br />A IEnumerable(T) collection with all the fields found.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim fields As IEnumerable(Of FieldInfo) = 
    GetAllFields(Of Form)(includeBaseTypes:=True)

For Each field As FieldInfo In fields
    Console.WriteLine(field.Name)
Next field
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllFields">GetAllFields Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />