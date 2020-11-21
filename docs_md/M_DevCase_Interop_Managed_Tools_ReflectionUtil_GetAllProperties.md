# ReflectionUtil.GetAllProperties Method (Object, Boolean, BindingFlags)
 

Gets all the properties declared in the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<PropertyInfo> GetAllProperties(
	Object obj,
	bool includeBaseTypes,
	BindingFlags bindingFlags = BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
)
```

**VB**<br />
``` VB
Public Shared Function GetAllProperties ( 
	obj As Object,
	includeBaseTypes As Boolean,
	Optional bindingFlags As BindingFlags = BindingFlags.DeclaredOnly Or BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic
) As IEnumerable(Of PropertyInfo)
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim includeBaseTypes As Boolean
Dim bindingFlags As BindingFlags
Dim returnValue As IEnumerable(Of PropertyInfo)

returnValue = ReflectionUtil.GetAllProperties(obj, 
	includeBaseTypes, bindingFlags)
```

**C++**<br />
``` C++
public:
static IEnumerable<PropertyInfo^>^ GetAllProperties(
	Object^ obj, 
	bool includeBaseTypes, 
	BindingFlags bindingFlags = BindingFlags::DeclaredOnly|BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic
)
```

**F#**<br />
``` F#
static member GetAllProperties : 
        obj : Object * 
        includeBaseTypes : bool * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
*)
-> IEnumerable<PropertyInfo> 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the properties.</dd><dt>includeBaseTypes</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), the search include properties declared in base types too.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: IEnumerable(PropertyInfo)<br />A IEnumerable(T) collection with all the properties found.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim props As IEnumerable(Of PropertyInfo) = GetAllProperties(Me, includeBaseTypes:=True)

For Each prop As PropertyInfo In props
    Console.WriteLine(prop.Name)
Next prop
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllProperties">GetAllProperties Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />