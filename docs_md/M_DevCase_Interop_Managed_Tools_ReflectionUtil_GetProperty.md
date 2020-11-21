# ReflectionUtil.GetProperty Method (Object, String, BindingFlags)
 

Searches for the specified property in the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PropertyInfo GetProperty(
	Object obj,
	string propName,
	BindingFlags bindingFlags = BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetProperty
)
```

**VB**<br />
``` VB
Public Shared Function GetProperty ( 
	obj As Object,
	propName As String,
	Optional bindingFlags As BindingFlags = BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic Or BindingFlags.FlattenHierarchy Or BindingFlags.GetProperty
) As PropertyInfo
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim propName As String
Dim bindingFlags As BindingFlags
Dim returnValue As PropertyInfo

returnValue = ReflectionUtil.GetProperty(obj, 
	propName, bindingFlags)
```

**C++**<br />
``` C++
public:
static PropertyInfo^ GetProperty(
	Object^ obj, 
	String^ propName, 
	BindingFlags bindingFlags = BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic|BindingFlags::FlattenHierarchy|BindingFlags::GetProperty
)
```

**F#**<br />
``` F#
static member GetProperty : 
        obj : Object * 
        propName : string * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetProperty
*)
-> PropertyInfo 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the property.</dd><dt>propName</dt><dd>Type: System.String<br />The name of the property to search for.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: PropertyInfo<br />A PropertyInfo instance that represents the obtained property.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Property not found using the current flags.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim prop As PropertyInfo = GetProperty(Me, "Text")
Dim text As String = DirectCast(prop.GetValue(Me), String)

Console.WriteLine(text)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetProperty">GetProperty Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />